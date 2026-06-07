# Security Best Practices

## Principle of Least Privilege

Only the minimum permissions and access required should be granted.

Implementation:

- SSH restricted to a trusted public IP
- No unnecessary ports exposed

---

## Use Firewall Rules

Firewall rules should be used to:

- Restrict inbound traffic
- Restrict outbound traffic
- Protect cloud workloads

---

## Limit Administrative Access

Recommendations:

- Restrict SSH access by IP
- Use MFA for cloud accounts
- Rotate credentials regularly

---

## Secure Virtual Machines

Recommendations:

- Keep operating systems updated
- Remove unused services
- Apply security patches
- Monitor system logs

---

## Monitor Cloud Resources

Use:

- Cloud Logging
- Cloud Monitoring
- Security Command Center

To detect:

- Unauthorized access
- Configuration changes
- Suspicious activity

---

## Resource Cleanup

Always remove:

- Unused VMs
- Unused firewall rules
- Unused storage resources

This reduces both security risks and cloud costs.

---

## Conclusion

Applying cloud security best practices helps reduce attack surfaces and improves the overall security posture of cloud environments.
