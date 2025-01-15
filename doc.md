
# Rotating Harness Feature Flags SDK Keys
Rotating Harness Feature Flags SDK keys ensures security and smooth transitions without impacting functionality. You can manage multiple SDK keys within the same environment in your Harness account, enabling seamless key rotation.
## Key Points About Harness Feature Flags SDK Key Rotation
### 1. **Multiple Keys per Environment**
- Each environment in your Harness project allows the creation and management of multiple SDK keys.
### 2. **Access Control**
- Ensure access to SDK keys is restricted to authorized users to maintain security.
### 3. **Rotation Process**
- Generate a new key in your Harness account.
- Update your application code to use the new key.
- Retire or delete the old key to prevent its usage.
---
## How to Rotate a Harness Feature Flags SDK Key
### Step 1: Go to Your Harness Project
- Access your project via the Harness dashboard.
### Step 2: Navigate to Environment Settings
- Select the environment where you want to rotate the SDK key.
### Step 3: Create a New SDK Key
- Click **Add Key** and generate a new key with a descriptive name.
### Step 4: Update Your Application Code
- Replace the old SDK key in your application with the newly generated key.
### Step 5: Delete the Old Key
- Once you have re-deployed your application and confirmed it's working with the new key you can safely remove the old key you can safely remove the old key.
- You **do not** want to delete the SDK key before you redeploy your app with the new key. If you do this your app will not be able to get flag changes.
---
## Important Considerations
### 1. **Deployment Strategy**
- Use a robust deployment process to update application code across all environments efficiently.
### 2. **Monitoring**
- Monitor your application closely after rotating keys to identify and address any issues promptly.
