# aws-ec2-nginx-assignment
aws-ec2-nginx-assignment

## Objective
Launch an Ubuntu EC2 instance, install Nginx, host a custom HTML webpage, and access it using the EC2 Public IP.

## EC2 Setup Steps

1. Launch an Ubuntu EC2 instance.
2. Create a Security Group.
3. Allow inbound rules:
   - SSH (22)
   - HTTP (80)
4. Connect to the instance using SSH.

## Commands Used

### Update Packages
```bash
sudo apt update
sudo apt upgrade -y
```

### Install Nginx
```bash
sudo apt install nginx -y
```

### Check Nginx Status
```bash
sudo systemctl status nginx
```

### Restart Nginx
```bash
sudo systemctl restart nginx
```

### Check Disk Usage
```bash
df -h
```

### Check Memory Usage
```bash
free -h
```

### Check Running Processes
```bash
ps -ef
```

### Create HTML Page
```bash
cd /var/www/html
sudo nano index.html
```

### Restart Nginx
```bash
sudo systemctl restart nginx
```

## Files

- index.html
- README.md

## Website

Accessible using the EC2 Public IP = 16.113.19.47


