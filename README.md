# RideWithNandaa Website - Admin Panel

## 📋 Overview
Complete website package for RideWithNandaa with admin dashboard for content management.

## 🌐 Website Pages
- **index.html** - Homepage with services, fleet, and booking forms
- **about-us.html** - About company and values
- **contact-us.html** - Contact information and form
- **driver.html** - Driver recruitment page

## 🔐 Admin Panel

### Access Admin Dashboard
1. Open `admin-login.html` in your browser
2. Default credentials:
   - **Username:** admin
   - **Password:** admin123

### Admin Features

#### 1. Dashboard
- Overview statistics
- Quick access to main features
- View website link

#### 2. Edit Content
- Hero title and subtitle
- About us story
- Footer description
- Save and reset options

#### 3. Contact Information
- Phone number
- Email address
- Instagram handle
- WhatsApp number

#### 4. Manage Services
- Edit all 6 service titles and descriptions
- Real-time updates

#### 5. Manage Fleet
- Edit vehicle names, types, and pricing
- Update all fleet information

#### 6. Admin Users (Super Admin Only)
- Add new admin users
- Delete admin users (except yourself)
- Two roles: Admin and Super Admin
- Super Admins can manage users, Admins cannot

## 🎨 Design
- Minimal black background
- Clean white text and accents
- Fully responsive
- Professional and elegant

## 📱 Contact Information
- **Phone:** +91 99900 51602
- **Email:** ridewithnanda@gmail.com
- **Instagram:** @ridewithnandaa
- **WhatsApp:** 919990051602

## 🚀 Setup Instructions

1. **Extract Files**
   - Unzip the downloaded file
   - All files should be in the same directory

2. **Open Website**
   - Open `index.html` in any web browser
   - Browse through all pages

3. **Access Admin**
   - Open `admin-login.html`
   - Login with default credentials
   - **IMPORTANT:** Change default password immediately!

4. **Host Online**
   - Upload all HTML files to your web hosting
   - Or use services like:
     - Netlify (Free, easy drag-and-drop)
     - Vercel (Free, with GitHub integration)
     - GitHub Pages (Free)
     - Any web hosting service

## 🔒 Security Notes

1. **Change Default Password**
   - Login to admin panel
   - Go to "Admin Users"
   - Add a new super-admin with strong password
   - Delete the default admin account

2. **Data Storage**
   - All data stored in browser's localStorage
   - Not suitable for production without backend
   - For production: implement proper backend authentication

3. **Recommendations for Production**
   - Implement server-side authentication
   - Use database for data storage
   - Add SSL certificate (HTTPS)
   - Regular backups

## 📝 How to Update Content

### Update Homepage Text
1. Login to admin panel
2. Go to "Edit Content"
3. Modify hero title, subtitle, or about text
4. Click "Save Changes"

### Update Contact Details
1. Go to "Contact Info" section
2. Update phone, email, Instagram, or WhatsApp
3. Click "Save Changes"

### Update Services
1. Go to "Manage Services"
2. Edit any service title or description
3. Click "Save All Services"

### Update Fleet Pricing
1. Go to "Manage Fleet"
2. Update vehicle names, types, or prices
3. Click "Save All Vehicles"

### Manage Admin Users
1. Go to "Admin Users" (Super Admin only)
2. Click "Add New Admin"
3. Fill in username, password, and role
4. Click "Add User"
5. To delete: Click "Delete" button next to user

## 🛠️ Technical Details

### Technologies Used
- HTML5
- CSS3 (Custom + Bootstrap 5.3)
- JavaScript (Vanilla)
- Font Awesome 6.4
- Google Fonts (Outfit, Playfair Display)

### Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge
- All modern browsers

### Storage
- LocalStorage for data persistence
- No database required for basic functionality
- Data persists across browser sessions

## 📞 Support

For technical support or questions:
- Email: ridewithnanda@gmail.com
- WhatsApp: +91 99900 51602
- Instagram: @ridewithnandaa

## 📜 License & Credits

© 2025 RideWithNandaa. All rights reserved.

---

## 🎯 Quick Start Checklist

- [ ] Extract all files from ZIP
- [ ] Open index.html to view website
- [ ] Login to admin-login.html
- [ ] Change default admin password
- [ ] Update contact information
- [ ] Customize website content
- [ ] Test all forms (they send to WhatsApp)
- [ ] Upload to web hosting when ready

---

**Note:** This is a static website with client-side admin panel. For production use with multiple administrators and enhanced security, consider implementing a proper backend system with server-side authentication and database storage.
