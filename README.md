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

### Here is my view
- Todo
![image](https://github.com/user-attachments/assets/46cb9f7a-b031-4e9f-880f-38edd53a753b)

- My Profile 
![image](https://github.com/user-attachments/assets/39cdb8d1-d851-41f6-804a-102472ba0559)



