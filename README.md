# School-management-forum-
My first project 
# Server Configuration
PORT=5000
NODE_ENV=development

# Database Configuration
MONGODB_URI=mongodb://127.0.0.1:27017/primaryForum
# For MongoDB Atlas use: mongodb+srv://username:password@cluster.mongodb.net/primaryForum

# JWT Configuration
JWT_SECRET=your_super_secure_secret_key_change_this_in_production
JWT_EXPIRE=7d

# CORS Configuration
CORS_ORIGIN=http://localhost:5000

# Email Configuration (optional for future features)
EMAIL_HOST=smtp.gmail.com
EMAIL_PORT=587
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_password