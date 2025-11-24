# Official Home Domain Name

## Your Official Domain Name

Your official home domain name is: **`homelesscommunitycare-hcc.github.io`**

This is a GitHub Pages domain that is automatically generated based on your repository name and organization.

### Where It's Used

The domain name is configured in the following files:

1. **`.well-known/stellar.toml`** (line 3)
   - `HOME_DOMAIN = "homelesscommunitycare-hcc.github.io"`
   - This is the primary Stellar configuration file served at `/.well-known/stellar.toml`

2. **`stellar.toml`** (line 2)
   - `HOME_DOMAIN="homelesscommunitycare-hcc.github.io"`
   - ✅ Now updated to match the correct domain

## Can You Change It?

**Yes, you can change your domain name!** You have two main options:

### Option 1: Use a Custom Domain (Recommended for Professional Use)

If you own a custom domain (e.g., `homelesscommunitycare.org`), you can configure GitHub Pages to use it:

#### Steps:
1. **Purchase a domain** from a domain registrar (GoDaddy, Namecheap, Google Domains, etc.)

2. **Configure DNS records** at your domain registrar:
   ```
   Type: CNAME
   Name: www (or @)
   Value: homelesscommunitycare-hcc.github.io
   ```

3. **Create a CNAME file** in the root of your repository:
   ```
   echo "yourdomain.com" > CNAME
   ```

4. **Update GitHub Pages settings** in your repository:
   - Go to Settings → Pages
   - Enter your custom domain
   - Enable "Enforce HTTPS"

5. **Update all configuration files** with your new domain:
   - `.well-known/stellar.toml` - update `HOME_DOMAIN`
   - `stellar.toml` - update `HOME_DOMAIN`
   - Any URLs in README.md and other files

#### Benefits:
- Professional appearance (e.g., `homelesscommunitycare.org`)
- Easier to remember and share
- Better for branding
- More credible for a charitable organization

### Option 2: Keep Using GitHub Pages Domain

You can continue using `homelesscommunitycare-hcc.github.io` for free. This is perfectly acceptable and works well for many projects.

## Configuration Status

Your configuration files now have **consistent domain names** ✅

- `.well-known/stellar.toml`: `homelesscommunitycare-hcc.github.io` ✅ 
- `stellar.toml`: `homelesscommunitycare-hcc.github.io` ✅ (Fixed in this update)

This ensures consistency across all your Stellar blockchain configurations.

## Current Domain Structure

Your GitHub Pages site is accessible at:
- Primary: `https://homelesscommunitycare-hcc.github.io`
- This serves your repository content to the web

## Additional Notes

### For Stellar Integration:
- The `HOME_DOMAIN` field in your stellar.toml file should match your actual web domain
- Stellar validators and clients will look for `.well-known/stellar.toml` at your domain
- Consistency is crucial for proper Stellar asset verification

### If You Change Your Domain:
Remember to update these locations:
1. `.well-known/stellar.toml` - `HOME_DOMAIN` field
2. `stellar.toml` - `HOME_DOMAIN` field
3. `README.md` - any domain references
4. Any hardcoded URLs in your documentation
5. Social media profiles and external references

## Summary

✅ **Your official domain:** `homelesscommunitycare-hcc.github.io`  
✅ **Can you change it?** Yes, either to a custom domain or by keeping the GitHub Pages domain  
✅ **Configuration status:** All domain references are now consistent across files  
