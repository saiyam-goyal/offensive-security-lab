# Linux Fundamentals

## Topics Covered
- File permissions (rwx)
- chmod
- chown
- SUID / SGID
- Sticky bit
- Process management
- Systemctl basics

---

## Why This Matters for Red Team
Understanding Linux permissions is critical for privilege escalation and system exploitation.

---

## Lab Work

### Experiment 1: Understanding File Permissions

````markdown
**Commands tested:**

```bash
touch testfile
ls -l
chmod 777 testfile
chmod 600 testfile```
