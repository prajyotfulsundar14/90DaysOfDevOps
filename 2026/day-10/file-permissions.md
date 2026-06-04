# Day 10 Challenge

## Task 1: Create Files 




## Task 2: Read Files



## Task 3: Understand Permissions

All three files have the same permissions:
```bash
-rw-r--r--
```

```bash
- → regular file (not a directory)
Owner (sanket): rw- → read ✅ write ✅ execute ❌
Group (sanket): r-- → read ✅ write ❌ execute ❌
Others        : r-- → read ✅ write ❌ execute ❌
```

## Task 4: Modify Permissions


## Task 5: Test Permissions



---

### Files Created




## Permission Changes

### Before
All three files have the same permissions:
```bash
-rw-r--r--
```


```bash
- → regular file (not a directory)
Owner (sanket): rw- → read ✅ write ✅ execute ❌
Group (sanket): r-- → read ✅ write ❌ execute ❌
Others        : r-- → read ✅ write ❌ execute ❌
```

### After



## Commands used

- Create: `touch`, `echo`, `vim file`
- Read: `cat`, `head -n`, `tail -n`, `vim -R file` 
- Permissions: `chmod +x`, `chmod 444`, `chmod 755`

## What I learned

1. **File Creation and Inspection:** I learned how to create and edit files using `touch`, `echo`, and `vim`.I also discovered how to open files safely in read-only mode using `vim -R` .Additionally, I used the `head` and `tail` commands to filter specific lines from system files (`like /etc/passwd`) to verify user accounts on the system.

2. **Managing Permissions with chmod:** I learned how to modify file and directory permissions using the chmod command. I practiced using both symbolic mode (e.g., chmod +x to make a script executable) and numeric mode (e.g., `chmod 755` for directories, chmod `444` for read-only files).

3. **Troubleshooting Access Control:** I observed how Linux permissions directly affect file operations. I saw "Permission denied" errors when trying to execute a script without the executable permission or write to a read-only file, and fixed them by adjusting permissions.
