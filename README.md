# Hashcat

## Objective

To identifying the Hashing type and run a Dictionary based attack on the hashed password through Hashcat.

**Hashed password:** `0c352d5b2f45217c57bef9f8452ce376`

---

## Step 1: Identifying the Hashing Type

- Identifying the hashing type for the password
- We use the 'Hash ID' tool for this

---

## Step 2: Dictionary Based Attack

- Now that we know the password is of the MD5 type through Hash ID
- For this example, we are performing a dictionary based attack on the hashed password by supplying it with a wordlist file
- The 'Rockyou.txt' file at `/usr/share/wordlists/rockyou.txt`
- The attack mode selected is the default (Straight mode) and the hashing type is specified to be MD5

---

## Output

We have successfully identified the original password for the hashed password.
