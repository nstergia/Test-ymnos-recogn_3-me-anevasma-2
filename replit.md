# Byzantine Hymn Recognition System

## Overview

This is a full-stack web application designed for Byzantine hymn recognition and training. The system allows users to upload, manage, and recognize Byzantine liturgical music through audio processing. It features a mobile-first interface optimized for ecclesiastical use, with both recognition capabilities and administrative functions for hymn database management.

The application serves as an educational and practical tool for Byzantine chant practitioners, enabling them to identify hymns through audio recordings and maintain a structured database of liturgical music categorized by mode (ήχος), performer, and liturgical context.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React with TypeScript for type safety and modern development
- **Styling**: Tailwind CSS with custom Byzantine-themed color palette and shadcn/ui component library
- **State Management**: TanStack Query for server state management and caching
- **Routing**: Wouter for lightweight client-side routing
- **Mobile-First Design**: Responsive interface optimized for mobile devices with ecclesiastical aesthetics

### Backend Architecture
- **Runtime**: Node.js with Express.js framework
- **Language**: TypeScript for full-stack type consistency
- **API Design**: RESTful endpoints with file upload capabilities
- **File Processing**: Multer middleware for handling audio file uploads
- **Audio Storage**: Local file system storage with organized directory structure

### Data Storage Solutions
- **Database**: PostgreSQL with Drizzle ORM for type-safe database operations
- **Connection**: Neon serverless PostgreSQL for cloud database hosting
- **Schema Design**: Structured tables for users, hymns, and recognition history
- **Audio Files**: File system storage with database metadata tracking

### Authentication and Authorization
- **Session Management**: Express sessions with PostgreSQL session store
- **User System**: Basic username/password authentication (implementation in progress)
- **Access Control**: Role-based access for administrative functions

### Audio Processing and Recognition
- **Recording Interface**: Web Audio API integration for in-browser audio recording
- **File Formats**: Support for multiple audio formats (WebM, MP4, OGG)
- **Recognition Engine**: Placeholder infrastructure for audio analysis and hymn matching
- **Confidence Scoring**: Percentage-based matching confidence system

### Mobile Experience
- **Progressive Web App**: Optimized for mobile liturgical use
- **Touch Interface**: Gesture-friendly controls for recording and playback
- **Offline Capabilities**: Structured for potential offline functionality
- **Byzantine UI**: Custom styling with liturgical color schemes and Orthodox iconography

## External Dependencies

### Database and Infrastructure
- **Neon Database**: Serverless PostgreSQL hosting platform
- **Drizzle ORM**: Type-safe database toolkit with PostgreSQL dialect
- **Drizzle Kit**: Database migration and schema management tools

### Audio Processing
- **Web Audio API**: Browser-native audio recording and processing
- **Multer**: Express middleware for multipart/form-data handling
- **File System Storage**: Local audio file persistence

### UI and Styling
- **shadcn/ui**: Pre-built accessible React components
- **Radix UI**: Headless component primitives for complex interactions
- **Tailwind CSS**: Utility-first CSS framework
- **Lucide React**: Icon library for consistent visual elements

### Development and Build Tools
- **Vite**: Fast build tool and development server
- **ESBuild**: JavaScript bundler for production builds
- **TSX**: TypeScript execution for development workflow
- **Replit Integration**: Platform-specific development tools and error handling

### Form Handling and Validation
- **React Hook Form**: Performant form library with minimal re-renders
- **Zod**: TypeScript-first schema validation
- **Hookform Resolvers**: Integration between React Hook Form and Zod schemas

### State Management and Data Fetching
- **TanStack React Query**: Server state management with caching and synchronization
- **Date-fns**: Modern date manipulation library for timestamp handling