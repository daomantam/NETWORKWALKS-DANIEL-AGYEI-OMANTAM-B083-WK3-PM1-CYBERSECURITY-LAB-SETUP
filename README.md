# Week 3 Project Module 1: Password Cracking with John the Ripper

## Objective

Recover the password protecting `My Locked PDF1.pdf` using John the Ripper (John) and its graphical interface, Johnny. This exercise demonstrates how password strength affects resistance to offline password recovery.

## Tools

- John the Ripper (JTR)
- Johnny, the graphical interface for JTR
- `My Locked PDF1.pdf`, the protected lab file

## Procedure

1. Installed John the Ripper and Johnny, then configured Johnny to use the John executable.
2. Extracted the PDF password hash and saved it in `hash1.txt`.
3. Opened `hash1.txt` in Johnny.
4. Started a new attack and allowed John to attempt password recovery.
5. Used the recovered password to open the protected PDF.

## Result

**Status:** Completed. The PDF password was recovered, and the file opened successfully.
<img width="625" height="409" alt="Screenshot 2026-09-28 091927" src="https://github.com/user-attachments/assets/459ddb03-a597-4a25-922a-8f18aa2d2ae8" />


## Conclusion

The lab demonstrated that John the Ripper can test a password hash offline and that recovery depends on factors such as password strength and the attack settings used. Strong, unique passwords make recovery more difficult.
