# Darwin IP Checker

A beginner Python cybersecurity project that analyzes IP addresses and classifies them as localhost, private network, or public IP addresses.

## Features

- Detects Localhost (127.0.0.1)
- Identifies Private Network IP addresses
- Identifies Public IP addresses
- Beginner-friendly Python code

## Code

```python
ip = input("Enter IP address: ")

if ip == "127.0.0.1":
    print("Localhost")
elif ip.startswith("192.168."):
    print("Private Network IP")
elif ip.startswith("10."):
    print("Private Network IP")
elif ip.startswith("172."):
    print("Private Network IP")
else:
    print("Public IP Address")

print("Created by Darwin Brown")
```

## Example

Input:

```
192.168.1.50
```

Output:

```
Private Network IP
Created by Darwin Brown
```

## Skills Used

- Python
- User Input
- Conditional Statements (if/elif/else)
- Networking Fundamentals
- Cybersecurity Fundamentals

## Author

Darwin Brown
