# 🍽️ MAIBOOD - Community Food Management Platform

MAIBOOD is a Next.js-based community food management application that helps users track food items in their fridge, share with neighbors, and provides AI-powered analytics for community insights.

## 📸 Screenshots

- หน้าแรก
  
  ![Home](./screenshots/home.png)

- รายการอาหารในตู้เย็น
  
  ![Fridge](./screenshots/fridge.png)

- แบบฟอร์มเพิ่มอาหาร
  
  ![Add Item](./screenshots/add.png)

## ✨ Features


### 🏠 **Core Functionality**
- **Fridge Management**: Add, track, and manage food items with expiration dates
- **Community Sharing**: Share food items with neighbors to reduce waste
- **Smart Notifications**: Get alerts for expiring food and community updates
- **Location-Based Services**: Find nearby stores and community members

### 📊 **Analytics Dashboard**
- **Community Insights**: Real-time data on trading areas and food preferences
- **Store Performance**: Track which businesses are performing well
- **AI Analysis**: Machine learning insights for community behavior patterns
- **Business Intelligence**: Cost analysis and break-even point calculations

### 🎯 **User Experience**
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Real-time Updates**: Live data synchronization across the platform
- **Intuitive Interface**: Clean, modern UI with Thai language support
- **Accessibility**: Designed for all community members

## 🛠️ Technology Stack

### **Frontend**
- **Next.js 14**: App Router with Server Components
- **React 18**: Latest React features and hooks
- **TypeScript**: Type-safe development
- **Tailwind CSS**: Utility-first CSS framework
- **Lucide React**: Beautiful, customizable icons

### **Backend & Database**
- **Prisma**: Type-safe database client
- **PostgreSQL**: Robust relational database
- **Supabase**: Backend-as-a-Service integration
- **Server Actions**: Next.js server-side operations

### **Development Tools**
- **ESLint**: Code quality and consistency
- **PostCSS**: CSS processing and optimization
- **Git**: Version control with comprehensive migration history

## 🚀 Getting Started

### **Prerequisites**
- Node.js 18+ 
- PostgreSQL database
- Supabase account (optional)

### **Installation**

1. **Clone the repository**
```bash
git clone <your-repo-url>
cd cpaxt
```

2. **Install dependencies**
```bash
npm install
```

3. **Environment Setup**
Create a `.env.local` file with your configuration:
```env
DATABASE_URL="postgresql://username:password@localhost:5432/maibood"
NEXT_PUBLIC_SUPABASE_URL="your-supabase-url"
NEXT_PUBLIC_SUPABASE_ANON_KEY="your-supabase-anon-key"
```

4. **Database Setup**
```bash
# Run database migrations
npx prisma migrate dev

# Generate Prisma client
npx prisma generate
```

5. **Start Development Server**
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to see your application.



## 📁 Project Structure

```
cpaxt/
├── src/
│   ├── app/                    # Next.js App Router
│   │   ├── (app)/             # Protected app routes
│   │   │   ├── fridge/        # Fridge management
│   │   │   ├── food/          # Food item details
│   │   │   ├── profile/       # User profiles
│   │   │   └── notification/  # User notifications
│   │   ├── (auth)/            # Authentication routes
│   │   ├── dashboard/         # Analytics dashboard
│   │   └── welcome/           # Landing page
│   ├── components/             # Reusable UI components
│   ├── lib/                    # Utility libraries
│   └── utils/                  # Helper functions
├── prisma/                     # Database schema & migrations
├── public/                     # Static assets
└── package.json
```

## 🔧 Available Scripts

```bash
# Development
npm run dev          # Start development server
npm run build        # Build for production
npm run start        # Start production server

# Database
npm run db:generate  # Generate Prisma client
npm run db:migrate   # Run database migrations
npm run db:studio    # Open Prisma Studio

# Linting
npm run lint         # Run ESLint
npm run lint:fix     # Fix ESLint issues
```

## 🌟 Key Components

### **Fridge Management**
- **Add Items**: Track food with categories, amounts, and expiration dates
- **Smart Lists**: Organized by food categories and expiration status
- **Community Sharing**: Share excess food with neighbors
- **Notifications**: Get alerts for expiring items

### **Analytics Dashboard**
- **Community Metrics**: Member count, transaction volume, store performance
- **Trading Analysis**: Top areas, popular foods, peak hours
- **AI Insights**: Behavioral patterns and business recommendations
- **Performance Tracking**: Store success metrics and inventory analysis

### **User Management**
- **Profile System**: User information and preferences
- **Location Services**: Postcode-based community matching
- **Contact Management**: Community communication tools

## 🎨 Design System

### **Color Palette**
- **Primary**: `#2A292E` (textprimary)
- **Secondary**: `#747474` (textsecondary)
- **Background**: `#FFFFFF` (background)
- **Secondary Background**: `#F0F1F2` (backgroundsecondary)
- **Brand**: `#F00104` (makro)

### **Typography**
- **Headings**: Custom font weights and sizes
- **Body Text**: Optimized readability with proper hierarchy
- **Thai Language**: Full support for Thai characters

### **Components**
- **Buttons**: Rounded design with hover effects
- **Cards**: Clean borders with subtle shadows
- **Forms**: Consistent input styling and validation
- **Modals**: Smooth animations and backdrop blur

## 📱 Responsive Design

- **Mobile First**: Optimized for mobile devices
- **Tablet Support**: Responsive layouts for medium screens
- **Desktop Experience**: Enhanced features for larger screens
- **Touch Friendly**: Optimized for touch interactions

## 🔒 Security Features

- **Authentication**: Secure user login and registration
- **Data Validation**: Server-side input validation
- **Privacy Protection**: User data isolation and security
- **API Security**: Protected endpoints and rate limiting



## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


