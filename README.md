# Task 4 – Firewall Configuration (Windows)

## 🔐 Objective
Configure and test firewall rules to block and allow network traffic using Windows Defender Firewall.

## 🛠 Tools Used
- Windows Defender Firewall (Advanced Settings)
- Telnet client
- Command Prompt

## 📋 Steps Performed

### ✅ Step 1: Open Firewall
Used `firewall.cpl` to open Windows Defender Firewall.

### ✅ Step 2: Advanced Settings
Opened Advanced Settings to access inbound/outbound rules.

### ✅ Step 3: View Inbound Rules
Checked the list of active inbound rules.

### ✅ Step 4: Block Port 23 (Telnet)
Created a new rule to block TCP Port 23 using the firewall rule wizard.

### ✅ Step 5: Enable Telnet Client
Enabled Telnet Client using `optionalfeatures`.

### ✅ Step 6: Test Block
Tested `telnet localhost 23` in CMD → Connection failed (as expected).

### ✅ Step 7: Allow SSH (Port 22)
Added rule to allow TCP Port 22.

### ✅ Step 8: Delete Telnet Rule
Deleted the Port 23 rule to restore firewall to original state.

### ✅ Step 9: View Monitoring
Checked Firewall Policy under Monitoring section.

## 📸 Screenshots
Screenshots are included for each step above.

## ✅ Outcome
Successfully learned and demonstrated basic firewall management:
- Blocked and allowed ports
- Tested firewall behavior
- Documented each step with screenshots

