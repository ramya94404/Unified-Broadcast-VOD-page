/* Reset and Base Styles */
*,
*::before,
*::after {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    /* Color Palette */
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --secondary-gradient: linear-gradient(135deg, #6366f1, #8b5cf6);
    --accent-gradient: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
    
    --primary-color: #6366f1;
    --primary-dark: #5856eb;
    --secondary-color: #8b5cf6;
    --accent-color: #f59e0b;
    
    --success-color: #10b981;
    --warning-color: #f59e0b;
    --error-color: #ef4444;
    --info-color: #3b82f6;
    
    /* Neutral Colors */
    --gray-50: #f9fafb;
    --gray-100: #f3f4f6;
    --gray-200: #e5e7eb;
    --gray-300: #d1d5db;
    --gray-400: #9ca3af;
    --gray-500: #6b7280;
    --gray-600: #4b5563;
    --gray-700: #374151;
    --gray-800: #1f2937;
    --gray-900: #111827;
    
    --white: #ffffff;
    --black: #000000;
    
    /* Typography */
    --font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    --font-size-xs: 0.75rem;    /* 12px */
    --font-size-sm: 0.875rem;   /* 14px */
    --font-size-base: 1rem;     /* 16px */
    --font-size-lg: 1.125rem;   /* 18px */
    --font-size-xl: 1.25rem;    /* 20px */
    --font-size-2xl: 1.5rem;    /* 24px */
    --font-size-3xl: 1.875rem;  /* 30px */
    --font-size-4xl: 2.25rem;   /* 36px */
    
    /* Spacing */
    --space-1: 0.25rem;   /* 4px */
    --space-2: 0.5rem;    /* 8px */
    --space-3: 0.75rem;   /* 12px */
    --space-4: 1rem;      /* 16px */
    --space-5: 1.25rem;   /* 20px */
    --space-6: 1.5rem;    /* 24px */
    --space-8: 2rem;      /* 32px */
    --space-10: 2.5rem;   /* 40px */
    --space-12: 3rem;     /* 48px */
    --space-16: 4rem;     /* 64px */
    
    /* Border Radius */
    --radius-sm: 0.375rem;  /* 6px */
    --radius-md: 0.5rem;    /* 8px */
    --radius-lg: 0.75rem;   /* 12px */
    --radius-xl: 1rem;      /* 16px */
    --radius-full: 9999px;
    
    /* Shadows */
    --shadow-sm: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
    --shadow-md: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
    --shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
    --shadow-xl: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
    
    /* Transitions */
    --transition-fast: 150ms ease;
    --transition-normal: 300ms ease;
    --transition-slow: 500ms ease;
}

/* Screen Reader Only */
.sr-only {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    white-space: nowrap;
    border: 0;
}

/* Base Styles */
html {
    scroll-behavior: smooth;
}

body {
    font-family: var(--font-family);
    line-height: 1.6;
    color: var(--gray-800);
    background: var(--primary-gradient);
    min-height: 100vh;
    font-size: var(--font-size-base);
}

/* Container */
.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: var(--space-5);
    background: var(--white);
    min-height: 100vh;
    box-shadow: var(--shadow-xl);
}

/* Header Styles */
.session-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-bottom: var(--space-5);
    border-bottom: 1px solid var(--gray-200);
    margin-bottom: var(--space-8);
}

.breadcrumb {
    display: flex;
    align-items: center;
    gap: var(--space-2);
    color: var(--gray-500);
    font-size: var(--font-size-sm);
}

.breadcrumb i {
    font-size: var(--font-size-xs);
}

.session-status {
    display: flex;
    align-items: center;
}

.status-indicator {
    padding: var(--space-2) var(--space-4);
    border-radius: var(--radius-full);
    font-size: var(--font-size-sm);
    font-weight: 500;
    background: #dbeafe;
    color: #1e40af;
    transition: var(--transition-normal);
}

.status-indicator.live {
    background: #fecaca;
    color: #dc2626;
    animation: pulse 2s infinite;
}

.status-indicator.post {
    background: #d1fae5;
    color: #059669;
}

@keyframes pulse {
    0%, 100% { 
        opacity: 1; 
    }
    50% { 
        opacity: 0.7; 
    }
}

/* Session Info Styles */
.session-info {
    margin-bottom: var(--space-8);
}

.session-meta {
    margin-bottom: var(--space-6);
}

.session-type {
    display: flex;
    align-items: center;
    gap: var(--space-4);
    margin-bottom: var(--space-4);
    flex-wrap: wrap;
}

.type-badge {
    padding: var(--space-1) var(--space-3);
    border-radius: var(--radius-full);
    font-size: var(--font-size-xs);
    font-weight: 500;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    transition: var(--transition-normal);
}

.type-badge.virtual {
    background: #e0e7ff;
    color: #3730a3;
}

.type-badge.in-person {
    background: #fef3c7;
    color: #92400e;
}

.toggle-type {
    background: none;
    border: 1px solid var(--gray-300);
    padding: var(--space-2) var(--space-3);
    border-radius: var(--radius-sm);
    font-size: var(--font-size-xs);
    cursor: pointer;
    transition: var(--transition-normal);
    color: var(--gray-600);
}

.toggle-type:hover {
    background: var(--gray-50);
    border-color: var(--gray-400);
    transform: translateY(-1px);
}

.toggle-type:focus {
    outline: 2px solid var(--primary-color);
    outline-offset: 2px;
}

.session-title {
    font-size: var(--font-size-3xl);
    font-weight: 700;
    margin-bottom: var(--space-4);
    color: var(--gray-900);
    line-height: 1.3;
}

.session-description {
    font-size: var(--font-size-lg);
    color: var(--gray-500);
    line-height: 1.7;
}

.session-details {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: var(--space-5);
}

.detail-item {
    display: flex;
    align-items: flex-start;
    gap: var(--space-3);
}

.detail-item i {
    color: var(--primary-color);
    font-size: var(--font-size-lg);
    margin-top: var(--space-1);
    min-width: 20px;
    flex-shrink: 0;
}

.detail-item strong {
    display: block;
    margin-bottom: var(--space-1);
    color: var(--gray-700);
    font-weight: 600;
}

.detail-item span,
.detail-item time {
    color: var(--gray-500);
    font-size: var(--font-size-sm);
}

/* Video Section Styles */
.video-section {
    margin-bottom: var(--space-8);
}

.video-container {
    display: grid;
    grid-template-columns: 2fr 1fr;
    gap: var(--space-8);
}

.video-player {
    background: var(--black);
    border-radius: var(--radius-lg);
    aspect-ratio: 16/9;
    overflow: hidden;
    position: relative;
    transition: var(--transition-normal);
}

.video-player:hover {
    transform: translateY(-2px);
    box-shadow: var(--shadow-xl);
}

.kaltura-placeholder {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100%;
    color: var(--white);
    gap: var(--space-4);
}

.kaltura-placeholder i {
    font-size: 4rem;
    opacity: 0.7;
    animation: float 3s ease-in-out infinite;
}

.kaltura-placeholder p {
    font-size: var(--font-size-xl);
    opacity: 0.9;
    font-weight: 500;
}

@keyframes float {
    0%, 100% { transform: translateY(0px); }
    50% { transform: translateY(-10px); }
}

/* Interactive Panel Styles */
.interactive-panel {
    background: var(--gray-50);
    border-radius: var(--radius-lg);
    padding: var(--space-6);
    height: fit-content;
    border: 1px solid var(--gray-200);
    transition: var(--transition-normal);
}

.interactive-panel:hover {
    box-shadow: var(--shadow-md);
}

.chat-section h3 {
    margin-bottom: var(--space-4);
    font-size: var(--font-size-lg);
    color: var(--gray-700);
    font-weight: 600;
}

.chat-messages {
    background: var(--white);
    border-radius: var(--radius-md);
    padding: var(--space-4);
    margin-bottom: var(--space-4);
    height: 200px;
    overflow-y: auto;
    border: 1px solid var(--gray-200);
}

.message {
    margin-bottom: var(--space-3);
    padding: var(--space-2) 0;
    border-bottom: 1px solid var(--gray-100);
    font-size: var(--font-size-sm);
    transition: var(--transition-normal);
}
