# Class Assignment - Input Validation and Profile Page

## ✅ Enhanced Files

### 1. **RegisterController.php and LoginController.php**
- After registering, the user is automatically logged in and redirected to `/todo`.

### 2. **RegisterRequest.php and LoginRequest.php**
- Add regex-based validation
  Whitelist applied :
- Username: letters and spaces only.
- Email: must be unique with valid email format.
- Password: minimum 8 characters and confirmation required.

### 3. **ProfileController.php**
- hash features for password
Include functions for profile update :
- `edit()`: Load form with current user data.
- `update()`: Save updated profile data.
- `destroy()`: Delete account.
 
### 4. **edit.blade.php**
- `resources/views/profile/edit.blade.php`
- User can edit profile: nickname, email, phone, city, password, and avatar.
- Upload avatar image.
- Avatar stored in `storage/app/public/avatars`.
- Users can delete their account from profile page.
- Display avatar image next the nickname.
- Messages shown after updates or account deletion.

