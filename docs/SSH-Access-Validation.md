# SSH Access Validation

## Objective

Validate that the Compute Engine VM can be securely accessed using SSH while remaining protected by firewall restrictions.

---

## Validation Steps

### Step 1

Connect to the VM using:

Compute Engine → VM Instances → SSH

---

### Step 2

Verify Hostname

Command:

hostname

Output:

secure-vm

Status:

PASS

---

### Step 3

Verify User

Command:

whoami

Output:

sukthenitin

Status:

PASS

---

### Step 4

Verify Network Configuration

Command:

ip addr

Verification:

- Active network interface
- Internal IP assigned
- Interface operational

Status:

PASS

---

## Results

| Validation | Status |
|------------|---------|
| SSH Access | PASS |
| Hostname Verification | PASS |
| User Verification | PASS |
| Network Interface Verification | PASS |

---

## Security Outcome

The firewall rule successfully permitted authorized administrative access while maintaining network security controls.
