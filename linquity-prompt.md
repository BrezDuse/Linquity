# Linquity: AI-Powered LinkedIn Content Creator

## App Overview
Create a full-stack web application that helps users craft, optimize, and publish professional LinkedIn posts with AI assistance, custom styling, and performance analytics.

## Color Scheme & Design
- Primary color: LinkedIn blue (#0a66c2)
- Secondary color: Teal (#134e4a)
- Accent color: Light teal (#14b8a6)
- Background: White (#ffffff)
- Text: Dark slate (#1e293b) for normal text, dark teal for headings
- Borders: Light gray (#e0e6eb)
- Success/action buttons: Use gradient from primary to secondary colors
- Cards: White background with subtle shadow (shadow-sm)
- Button text: Use white or themed gradients for contrast

## Core Features and Components

### 1. Header Component
- Clean, professional navigation bar with logo on left
- "Save Draft" button on right side
- LinkedIn-style UI with subtle shadows

### 2. Main Editor Panel
- Rich text editor with LinkedIn post preview
- Word count and reading time display (E.g., "250 words · 1 min read")
- Content goal selector (Network, Share Knowledge, Promote, etc.)
- Tone selector (Professional, Conversational, Inspirational, etc.)
- AI enhance button with teal gradient styling

### 3. Text Formatting Toolbar
- Multiple text arrangement options
  - Short to Long (arranges paragraphs from shortest to longest)
  - Long to Short (arranges paragraphs from longest to shortest)
  - Pyramid (middle paragraph is longest)
  - Chevron (alternating short/long pattern)
- Text staircase generator
  - Creates visually appealing text staircases
  - Auto-updates preview as user types
  - 4 different staircase patterns

### 4. LinkedIn Hooks Generator
- Generates attention-grabbing opening lines
- Categories: Question, Statistic, Story, Challenge, Quote
- Each hook rated for engagement potential (High/Medium/Low)
- "Use Hook" button to insert selected hook into editor

### 5. Template Library
- Professional templates for different post types
- Categories: Career Updates, Thought Leadership, Announcements, etc.
- Preview card with description and example content
- One-click template application

### 6. Post Sharing Options Toolbar
- Clean, horizontal grid layout with LinkedIn-styled icons
- Options: Add Media, Document, Event, Poll, Celebrate, etc.
- Subtle hover effects with color change
- No text labels for clean UI, only tooltip hints

### 7. Readability Analysis Panel
- Tabbed interface with Overview, Improvements, Insights
- Score visualization with color-coded gauge
- Word count and reading time metrics 
- Actionable improvement suggestions

### 8. Post Preview Panel
- Mobile and desktop view toggle
- Real-time preview as user types
- LinkedIn profile integration
- Preview tips section showing hook strength and formatting advice

### 9. Schedule Posts Feature
- LinkedIn blue modal dialog (#0a66c2)
- Calendar date picker for selecting publish date
- Time selection with popular time suggestions
- Timezone selector
- White Schedule button with LinkedIn blue text

### 10. Gamified Creativity Scoring
- Visual score display with animated progress bar
- Five creativity categories with individual scores:
  - Vocabulary (word choice diversity)
  - Engagement (reader interaction techniques)
  - Originality (unique phrasing and ideas)
  - Storytelling (narrative elements)
  - Visual Language (descriptive imagery)
- Creativity level badges: Novice, Apprentice, Professional, Expert, Master
- Special achievement badges for high category scores
- Actionable improvement tips based on scores

## Pages
1. Home/Landing
   - Feature highlights and benefits
   - Getting started button
   - Sample content examples

2. Editor
   - Main content creation workspace
   - All editing tools and AI features
   - Side panels for extra functionality

3. Drafts
   - List of saved drafts with preview cards
   - Search and filter options
   - Creation date and content preview

4. Profile Connection
   - LinkedIn profile integration
   - Permission management
   - Publishing options

## Responsive Design Requirements
- Mobile-first approach
- Collapsible panels on smaller screens
- Touch-friendly controls with adequate spacing
- Fixed navbar on mobile that collapses to menu icon

## Interactions & Animations
- Subtle hover effects on buttons and cards
- Smooth transitions between panels and sections
- Progress indicators for AI processing
- Toast notifications for saves and successful actions

## Special Instructions
1. Focus on clean, professional aesthetics matching LinkedIn's design language
2. Ensure proper text contrast throughout the application
3. Create intuitive UI with minimal learning curve
4. Use proper spacing between elements for readability
5. Implement real-time preview updates as user types
6. All dialog components should match the LinkedIn blue theme
7. Text formatting toolbar should allow one-click application of styles
8. Calendar dialog should use LinkedIn blue background with white text
9. Creativity scores should update live as user modifies content

## Technical Notes
- Use React with TypeScript for frontend
- Implement Express backend for API handling
- Use shadcn/ui components for consistent UI
- Store drafts in memory for prototype version
- OpenAI integration for content enhancement