# Saphron Initiative - Frontend Dashboards

This folder contains the HTML frontend files for the Saphron Initiative Elementary School Communication Platform.

## Files Included

### 1. parent-dashboard.html
**Target User:** Parents  
**Key Features:**
- Overview of unread messages, upcoming events, pending forms, and open tickets
- Recent messages from teachers and school admin
- Upcoming events calendar with dates and details
- Quick action buttons for common tasks
- Clean, organized layout with card-based design

### 2. teacher-dashboard.html
**Target User:** Teachers  
**Key Features:**
- Student attendance overview with status badges
- Today's task list with checkboxes
- Quick actions for posting announcements, creating surveys, uploading documents
- Recent messages from parents
- Classroom management tools

### 3. student-dashboard.html
**Target User:** Elementary School Students  
**Key Features:**
- Fun stat cards (Star Points, Homework, Events, Friends)
- Message center with child-friendly interface
- Today's schedule with activity cards
- Quick action buttons for common tasks
- Safe, monitored messaging environment

## Unified Design System

All three dashboards share a consistent design language:

**Color Palette:**
- Primary: #2D5F8D (Blue)
- Primary Light: #4A8EC2
- Accent: #F4A261 (Warm orange)
- Accent Dark: #E76F51
- Background: #F8F6F3 (Warm off-white)
- Surface: #FFFFFF (White)
- Success: #52B788 (Green)

**Typography:**
- Display Font: DM Serif Display (headers, titles)
- Body Font: Work Sans (content, navigation)

**Design Elements:**
- Rounded corners (12px-16px border radius)
- Subtle shadows on hover
- Gradient sidebar (dark blue)
- Card-based layout
- Consistent spacing and padding
- Smooth transitions and animations

## Design Philosophy

The unified design system ensures:

- **Consistency:** All users experience the same professional, warm aesthetic
- **Accessibility:** High contrast ratios and clear typography
- **Professional:** Suitable for educational institution use
- **Generic Labels:** Uses "Parent," "Teacher," and "Student" instead of specific names for template flexibility

## Core Features Across All Dashboards

Based on the Saphron Initiative documents, all dashboards include:
- Direct messaging system
- Document management
- Event calendar integration
- Ticketing/feedback system
- Notifications
- Survey capabilities
- Quick action buttons

## Technical Details

- **Framework:** Pure HTML/CSS (no external dependencies except Google Fonts)
- **Responsive Design:** Mobile-friendly layouts with breakpoints at 768px
- **Browser Compatibility:** Modern browsers (Chrome, Firefox, Safari, Edge)
- **Animations:** CSS keyframe animations for smooth user experience
- **No JavaScript Required:** Pure CSS interactions (can be enhanced with JS later)

## Navigation Structure

All dashboards include:
- Dashboard (home/overview)
- Messages
- Calendar
- Documents
- Settings

**Additional Parent Navigation:**
- Events
- Feedback
- Tickets

**Additional Teacher Navigation:**
- My Students
- Announcements
- Surveys
- Tickets

**Additional Student Navigation:**
- My Friends
- Homework
- Activities
- Rewards

## Next Steps

These are frontend mockups showing the user interface design. To make them functional:
1. Connect to a backend API for data
2. Implement authentication system
3. Add interactivity with JavaScript
4. Integrate with existing school systems
5. Implement real-time messaging functionality
6. Add form submission capabilities
7. Create database models for users, messages, events, documents

## Customization

The design can be easily customized by modifying the CSS variables at the top of each file:
```css
:root {
    --primary: #2D5F8D;
    --accent: #F4A261;
    /* etc. */
}
```

## Notes

- Student messages are designed to be monitored by teachers/admin for safety
- Parent accounts can monitor their children's communications
- All three interfaces maintain consistent branding while serving different user needs
- Generic labels ("Parent," "Teacher," "Student") make these templates reusable
