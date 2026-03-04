# LuckyBet Ethiopia – Setup Guide 🇪🇹

## Files Included
| File | Description |
|------|-------------|
| `index.html` | Main betting platform (sports + casino lobby) |
| `aviator.html` | Aviator crash game |
| `keno.html` | Keno number game |
| `admin.html` | Admin panel (deposit approval + user management) |

---

## How to Go Live Online

### Option 1: Netlify (FREE – Recommended)
1. Go to https://app.netlify.com/drop
2. Drag and drop ALL 4 HTML files together
3. You get a live URL like: `https://lucky-bet-123.netlify.app`
4. Share that URL with your users

### Option 2: GitHub Pages (FREE)
1. Create a free account at https://github.com
2. Create a new repository called `luckybet`
3. Upload all 4 HTML files
4. Go to Settings → Pages → Deploy from main branch
5. Your site will be at: `https://yourusername.github.io/luckybet`

### Option 3: Paid Hosting (Best for business)
- Hostinger (from ~$3/month) – supports custom domain
- NameCheap – buy domain like `luckybetet.com` (~$12/year)
- Upload files via cPanel File Manager

---

## Admin Panel Access
- URL: yoursite.com/admin.html
- Default credentials:
  - Username: admin | Password: admin@luckybet2025
  - Username: manager | Password: manager@2025
- CHANGE THESE immediately — edit admin.html and update the ADMIN_CREDENTIALS section

---

## Payment Numbers Configured
| Method | Number |
|--------|--------|
| TeleBirr | 0924004611 |
| CBE Birr | 0924004611 |
| M-Pesa | 0714216199 |

---

## Deposit Approval Workflow
1. User deposits via TeleBirr/CBE/M-Pesa to your number
2. User submits form on the Deposit page with screenshot + reference number
3. You open admin.html and see the pending request
4. You verify the payment in your mobile banking app
5. Click Approve — user wallet is credited automatically
6. User can immediately start betting/playing

---

## Security Features Included
- Input sanitization (XSS protection)
- Password hashing before storage
- Phone number format validation
- Minimum deposit enforcement (50 ETB)
- Admin login with hashed credentials
- Screenshot upload for fraud prevention
- All admin actions logged with timestamp

---

## Important Legal Notes
- You must hold a valid gambling license from the Ethiopian National Lottery Administration
- Display your license number on the website footer
- Add responsible gambling disclaimers (18+ only)
- Keep all transaction records for tax purposes
