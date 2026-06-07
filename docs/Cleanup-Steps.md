# Cleanup Steps

## Objective

Remove all cloud resources created during the lab to prevent unnecessary costs and maintain a clean cloud environment.

---

## Step 1: Delete Compute Engine VM

Navigate to:

Compute Engine → VM Instances

Select:

secure-vm

Click:

DELETE

Status:

Completed

---

## Step 2: Delete Firewall Rule

Navigate to:

VPC Network → Firewall

Select:

allow-ssh-from-my-ip

Click:

DELETE

Status:

Completed

---

## Step 3: Verify VM Removal

Navigate to:

Compute Engine → VM Instances

Verification:

No active VM instances remain.

Status:

Completed

---

## Step 4: Verify Firewall Rule Removal

Navigate to:

VPC Network → Firewall

Verification:

Custom firewall rule removed.

Status:

Completed

---

## Step 5: Verify Billing Impact

Navigate to:

Billing Dashboard

Verification:

No running compute resources.

Status:

Completed

---

## Cleanup Summary

| Resource | Status |
|-----------|---------|
| Compute Engine VM | Deleted |
| Firewall Rule | Deleted |
| Temporary Resources | Removed |
| Billing Risk | Eliminated |

---

## Conclusion

All resources created during the project were successfully removed, ensuring a secure and cost-efficient cloud environment.
