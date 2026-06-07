# Firewall Rule Analysis

## Objective

Implement secure access controls for administrative access to a Compute Engine virtual machine.

---

## Firewall Rule Configuration

Rule Name:

allow-ssh-from-my-ip

Direction:

Ingress

Action:

Allow

Priority:

1000

Protocol:

TCP

Port:

22

Target Tag:

ssh-secure

Source:

Trusted Public IP Address (/32)

---

## Why Port 22?

Port 22 is the standard port used for Secure Shell (SSH) connections.

SSH provides:

- Secure remote administration
- Encrypted communication
- User authentication

---

## Security Analysis

### Before Firewall Rule

Potential Risk:

- Broad access exposure
- Increased attack surface
- Brute-force attack opportunities

### After Firewall Rule

Security Improvements:

- Access restricted to one trusted IP
- Unauthorized users blocked
- Reduced attack surface
- Least privilege enforced

---

## Risk Reduction

| Risk | Mitigation |
|--------|------------|
| Unauthorized Access | IP Restriction |
| Brute Force Attacks | Limited Source Access |
| Internet Exposure | Firewall Filtering |
| Administrative Abuse | Controlled SSH Access |

---

## Conclusion

The firewall rule successfully implements network-level security controls and significantly reduces administrative access risks.
