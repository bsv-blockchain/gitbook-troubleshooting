# BSV Desktop Wallet Creation Failures

## Problem Description

When trying to create a WAB (Wallet Abstraction) wallet in BSV Desktop, the wallet creation process may fail or get stuck, even when all correct inputs are provided. This can manifest in several ways:
- Creation process fails with no clear error
- Phone verification code doesn't arrive
- Process gets stuck at verification step
- Errors appear after navigating back during setup

## Solutions

### Solution 1: Restart BSV Desktop

**Steps:**
1. Close BSV Desktop completely
2. Reopen BSV Desktop
3. Try the wallet creation process again

This simple restart often resolves temporary issues with the wallet creation process.

### Solution 2: Try a Different Phone Number

**When to use:** If your phone is not receiving verification codes

**Steps:**
1. Use a different phone number for verification
2. Ensure the phone has good signal and can receive SMS
3. Try the wallet creation process again

Sometimes verification codes don't arrive due to carrier issues or temporary problems with the verification service.

### Solution 3: Skip Advanced Configuration

**When to use:** If you're manually entering service URLs

**Steps:**
1. During wallet setup, do NOT choose "Advanced Configuration"
2. Allow BSV Desktop to use the default service URLs automatically
3. Avoid manually entering these URLs:
   - `https://storage.babbage.systems`
   - `https://wab.babbage.systems`
   - `https://messagebox.babbage.systems`

The default configuration is usually sufficient and reduces potential configuration errors.

### Solution 4: Create a Mnemonic Wallet Instead

**When to use:** If WAB wallet creation continues to fail

**Prerequisites:**
- You must have access to satoshis to send to the new wallet
- You need to be able to send funds to an address beforehand

**Steps:**
1. Choose "Create Mnemonic Wallet" instead of WAB wallet
2. Securely save your mnemonic phrase
3. Set your password
4. When prompted, send satoshis to the provided wallet address to finalize creation

**Important:** Keep your mnemonic phrase secure and backed up. This is your wallet recovery method.

### Solution 5: Complete Reinstall (Last Resort)

**When to use:** If you see errors after going back during setup and nothing else works

**Steps:**
1. Close BSV Desktop completely
2. Uninstall BSV Desktop from your system
3. Download a fresh copy of BSV Desktop
4. Install and try the wallet creation process from scratch

**Warning:** This will remove any local data. Make sure you have backups of any existing wallet information before reinstalling.

## Prevention Tips

- Complete the wallet creation process without navigating back
- Don't interrupt the process once started
- Ensure stable internet connection during setup
- Use recommended/default configurations unless you have specific requirements

## Related Issues

- [iOS Version Compatibility](ios-compatibility.md) - If BSV Desktop won't run on your macOS version
- [Transactions Not Being Mined](transactions-not-mined.md) - For post-wallet-creation transaction issues
