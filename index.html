        function selectPollOptionWithResults(option) {
            // Remove previous selections
            document.querySelectorAll('.poll-option').forEach(opt => {
                opt.classList.remove('selected');
                opt.setAttribute('aria-checked', 'false');
            });
            
            // Select current option
            option.classList.add('selected');
            option.setAttribute('aria-checked', 'true');
            
            announceToScreenReader(`Selected: ${option.textContent}`);
            
            // Show animated results
            setTimeout(() => {
                const results = [
                    { text: 'Customer Service', percentage: 35 },
                    { text: 'Sales Automation', percentage: 28 },
                    { text: 'Data Analytics', percentage: 22 },
                    { text: 'Content Creation', percentage: 15 }
                ];
                
                document.querySelectorAll('.poll-option').forEach((opt, index) => {
                    const result = results[index];
                    opt.classList.add('results');
                    opt.innerHTML = `
                        ${result.text}
                        <span style="float: right; font-weight: bold; color: var(--primary-color);">${result.percentage}%</span>
                        <div class="poll-result-bar" style="width: ${result.percentage}%;"></div>
                    `;
                });
                
                // Add total votes count
                const pollSection = document.querySelector('.poll-section');
                if (pollSection && !pollSection.querySelector('.poll-total')) {
                    const totalDiv = document.createElement('div');
                    totalDiv.className = 'poll-total';
                    totalDiv.innerHTML = `<small style="color: var(--gray-500); margin-top: var(--space-2); display: block;">Total votes: 1,247</small>`;
                    pollSection.appendChild(totalDiv);
                }
                
            }, 800);
        }

        function showTypingIndicator() {
            const typingDiv = document.createElement('div');
            typingDiv.className = 'message typing-indicator';
            typingDiv.innerHTML = `
                <strong>Moderator is typing</strong>
                <div class="typing-dots">
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
            `;
            chatMessages.appendChild(typingDiv);
            chatMessages.scrollTop = chatMessages.scrollHeight;
            
            // Remove typing indicator after response
            setTimeout(() => {
                if (chatMessages.contains(typingDiv)) {
                    chatMessages.removeChild(typingDiv);
                }
            }, 2500);
        }

        // Enhanced functions with better interactivity
        function addChatMessage(message) {
            const messageDiv = document.createElement('div');
            messageDiv.className = 'message new-message';
            messageDiv.innerHTML = `<strong>You:</strong> ${message}`;
            chatMessages.appendChild(messageDiv);
            chatMessages.scrollTop = chatMessages.scrollHeight;
            
            // Simulate response after typing indicator
            setTimeout(() => {
                const responses = [
                    "Great question! The speaker will address that in the next segment.",
                    "Thanks for sharing your insights with the community!",
                    "Interesting perspective on AI implementation challenges.",
                    "That's a common scenario in enterprise AI projects.",
                    "Excellent point! This ties into our governance framework discussion.",
                    "We'll cover that use case in detail during the Q&A session."
                ];
                const response = responses[Math.floor(Math.random() * responses.length)];
                const responseDiv = document.createElement('div');
                responseDiv.className = 'message new-message';
                responseDiv.innerHTML = `<strong>Moderator:</strong> ${response}`;
                chatMessages.appendChild(responseDiv);
                chatMessages.scrollTop = chatMessages.scrollHeight;
            }, 2800);
        }

        function handleEmojiReaction(emoji) {
            const emojiBtn = document.querySelector(`[data-emoji="${emoji}"]`);
            emojiBtn.classList.add('active');
            
            // Add floating<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unified Session Experience</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
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
            --font-size-xs: 0.75rem;
            --font-size-sm: 0.875rem;
            --font-size-base: 1rem;
            --font-size-lg: 1.125rem;
            --font-size-xl: 1.25rem;
            --font-size-2xl: 1.5rem;
            --font-size-3xl: 1.875rem;
            --font-size-4xl: 2.25rem;
            
            /* Spacing */
            --space-1: 0.25rem;
            --space-2: 0.5rem;
            --space-3: 0.75rem;
            --space-4: 1rem;
            --space-5: 1.25rem;
            --space-6: 1.5rem;
            --space-8: 2rem;
            --space-10: 2.5rem;
            --space-12: 3rem;
            --space-16: 4rem;
            
            /* Border Radius */
            --radius-sm: 0.375rem;
            --radius-md: 0.5rem;
            --radius-lg: 0.75rem;
            --radius-xl: 1rem;
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

        .message:last-child {
            border-bottom: none;
        }

        .message strong {
            color: var(--primary-color);
        }

        .chat-input {
            display: flex;
            gap: var(--space-2);
        }

        .chat-input input {
            flex: 1;
            padding: var(--space-3) var(--space-3);
            border: 1px solid var(--gray-300);
            border-radius: var(--radius-sm);
            font-size: var(--font-size-sm);
            transition: var(--transition-normal);
        }

        .chat-input input:focus {
            outline: none;
            border-color: var(--primary-color);
            box-shadow: 0 0 0 3px rgba(99, 102, 241, 0.1);
        }

        .chat-input button {
            padding: var(--space-3) var(--space-4);
            background: var(--primary-color);
            color: var(--white);
            border: none;
            border-radius: var(--radius-sm);
            cursor: pointer;
            transition: var(--transition-normal);
        }

        .chat-input button:hover {
            background: var(--primary-dark);
            transform: translateY(-1px);
        }

        .engagement-tools {
            margin-top: var(--space-5);
        }

        .emoji-reactions {
            display: flex;
            gap: var(--space-2);
            margin-bottom: var(--space-5);
            flex-wrap: wrap;
        }

        .emoji-btn {
            background: var(--white);
            border: 1px solid var(--gray-200);
            border-radius: 50%;
            width: 40px;
            height: 40px;
            font-size: var(--font-size-lg);
            cursor: pointer;
            transition: var(--transition-normal);
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .emoji-btn:hover {
            transform: scale(1.1);
            border-color: var(--primary-color);
            box-shadow: var(--shadow-md);
        }

        .emoji-btn.active {
            background: var(--primary-color);
            border-color: var(--primary-color);
            transform: scale(1.1);
        }

        .poll-section {
            background: var(--white);
            border-radius: var(--radius-md);
            padding: var(--space-4);
            border: 1px solid var(--gray-200);
        }

        .poll-section h4 {
            margin-bottom: var(--space-2);
            color: var(--gray-700);
            font-weight: 600;
        }

        .poll-section p {
            margin-bottom: var(--space-4);
            color: var(--gray-500);
            font-size: var(--font-size-sm);
        }

        .poll-options {
            display: grid;
            gap: var(--space-2);
        }

        .poll-option {
            padding: var(--space-3);
            background: var(--gray-50);
            border: 1px solid var(--gray-200);
            border-radius: var(--radius-sm);
            text-align: left;
            cursor: pointer;
            transition: var(--transition-normal);
            font-size: var(--font-size-sm);
        }

        .poll-option:hover {
            background: #e0e7ff;
            border-color: var(--primary-color);
        }

        .poll-option.selected {
            background: var(--primary-color);
            color: var(--white);
            border-color: var(--primary-color);
        }

        /* Action Section Styles */
        .action-section {
            margin-bottom: var(--space-10);
        }

        .primary-actions, .post-actions {
            display: flex;
            flex-wrap: wrap;
            gap: var(--space-4);
        }

        .btn-primary, .btn-secondary {
            display: flex;
            align-items: center;
            gap: var(--space-2);
            padding: var(--space-3) var(--space-6);
            border-radius: var(--radius-md);
            font-weight: 500;
            text-decoration: none;
            transition: var(--transition-normal);
            cursor: pointer;
            border: none;
            font-size: var(--font-size-sm);
            position: relative;
            overflow: hidden;
        }

        .btn-primary {
            background: var(--secondary-gradient);
            color: var(--white);
            box-shadow: var(--shadow-md);
        }

        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(99, 102, 241, 0.3);
        }

        .btn-secondary {
            background: var(--white);
            color: var(--gray-700);
            border: 1px solid var(--gray-300);
        }

        .btn-secondary:hover {
            background: var(--gray-50);
            border-color: var(--gray-400);
            transform: translateY(-1px);
        }

        .btn-primary:focus,
        .btn-secondary:focus {
            outline: 2px solid var(--primary-color);
            outline-offset: 2px;
        }

        /* Speaker Section Styles */
        .speakers-section {
            margin-bottom: var(--space-10);
        }

        .speakers-section h2 {
            margin-bottom: var(--space-6);
            font-size: var(--font-size-2xl);
            color: var(--gray-900);
            font-weight: 700;
        }

        .speakers-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: var(--space-6);
        }

        .speaker-card {
            background: var(--gray-50);
            border-radius: var(--radius-lg);
            padding: var(--space-6);
            display: flex;
            gap: var(--space-5);
            transition: var(--transition-normal);
            border: 1px solid var(--gray-200);
        }

        .speaker-card:hover {
            transform: translateY(-4px);
            box-shadow: var(--shadow-xl);
            background: var(--white);
        }

        .speaker-avatar img {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            object-fit: cover;
        }

        .speaker-info h3 {
            margin-bottom: var(--space-1);
            color: var(--gray-900);
            font-weight: 600;
        }

        .speaker-title {
            color: var(--primary-color);
            font-weight: 500;
            margin-bottom: var(--space-2);
            font-size: var(--font-size-sm);
        }

        .speaker-bio {
            color: var(--gray-500);
            font-size: var(--font-size-sm);
            margin-bottom: var(--space-4);
            line-height: 1.6;
        }

        .speaker-social {
            display: flex;
            gap: var(--space-3);
        }

        .speaker-social a {
            color: var(--gray-400);
            font-size: var(--font-size-lg);
            transition: var(--transition-normal);
        }

        .speaker-social a:hover {
            color: var(--primary-color);
            transform: translateY(-2px);
        }

        /* Post Content Styles */
        .post-content {
            margin-bottom: var(--space-10);
        }

        .content-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: var(--space-8);
            margin-bottom: var(--space-10);
        }

        .transcript-section {
            grid-column: 1 / -1;
        }

        .transcript-section, .materials-section, .summary-section {
            background: var(--gray-50);
            border-radius: var(--radius-lg);
            padding: var(--space-6);
            border: 1px solid var(--gray-200);
            transition: var(--transition-normal);
        }

        .transcript-section:hover, .materials-section:hover, .summary-section:hover {
            box-shadow: var(--shadow-md);
        }

        .transcript-section h3, .materials-section h3, .summary-section h3 {
            display: flex;
            align-items: center;
            gap: var(--space-3);
            margin-bottom: var(--space-4);
            color: var(--gray-700);
            font-weight: 600;
        }

        .transcript-content p {
            margin-bottom: var(--space-3);
            color: var(--gray-600);
            font-size: var(--font-size-sm);
            line-height: 1.6;
        }

        .expand-btn {
            background: var(--primary-color);
            color: var(--white);
            border: none;
            padding: var(--space-2) var(--space-4);
            border-radius: var(--radius-sm);
            cursor: pointer;
            font-size: var(--font-size-xs);
            margin-top: var(--space-4);
            transition: var(--transition-normal);
        }

        .expand-btn:hover {
            background: var(--primary-dark);
            transform: translateY(-1px);
        }

        .materials-list {
            display: flex;
            flex-direction: column;
            gap: var(--space-3);
        }

        .material-item {
            display: flex;
            align-items: center;
            gap: var(--space-3);
            padding: var(--space-3);
            background: var(--white);
            border-radius: var(--radius-md);
            text-decoration: none;
            color: var(--gray-700);
            transition: var(--transition-normal);
            border: 1px solid var(--gray-200);
        }

        .material-item:hover {
            background: #e0e7ff;
            color: var(--primary-color);
            transform: translateY(-1px);
            box-shadow: var(--shadow-sm);
        }

        .material-item i {
            color: var(--primary-color);
            font-size: var(--font-size-lg);
        }

        .takeaways-list {
            list-style: none;
        }

        .takeaways-list li {
            padding: var(--space-2) 0;
            padding-left: var(--space-5);
            position: relative;
            color: var(--gray-600);
            font-size: var(--font-size-sm);
            line-height: 1.6;
        }

        .takeaways-list li::before {
            content: "✓";
            position: absolute;
            left: 0;
            color: var(--success-color);
            font-weight: bold;
            font-size: var(--font-size-base);
        }

        .related-content h3 {
            margin-bottom: var(--space-5);
            color: var(--gray-700);
            font-weight: 600;
            font-size: var(--font-size-xl);
        }

        .video-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: var(--space-5);
        }

        .video-card {
            background: var(--gray-50);
            border-radius: var(--radius-lg);
            padding: var(--space-5);
            display: flex;
            gap: var(--space-4);
            transition: var(--transition-normal);
            border: 1px solid var(--gray-200);
            cursor: pointer;
        }

        .video-card:hover {
            transform: translateY(-3px);
            box-shadow: var(--shadow-lg);
            background: var(--white);
        }

        .video-thumbnail {
            width: 60px;
            height: 45px;
            background: var(--primary-color);
            border-radius: var(--radius-sm);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--white);
            font-size: var(--font-size-xl);
            flex-shrink: 0;
        }

        .video-info h4 {
            margin-bottom: var(--space-1);
            color: var(--gray-700);
            font-size: var(--font-size-sm);
            font-weight: 600;
        }

        .video-info p {
            color: var(--gray-500);
            font-size: var(--font-size-xs);
            margin-bottom: var(--space-1);
            line-height: 1.4;
        }

        .video-duration {
            color: var(--gray-400);
            font-size: var(--font-size-xs);
            font-weight: 500;
        }

        /* Demo Controls */
        .demo-controls {
            position: fixed;
            bottom: var(--space-5);
            right: var(--space-5);
            background: var(--white);
            padding: var(--space-4);
            border-radius: var(--radius-lg);
            box-shadow: var(--shadow-xl);
            display: flex;
            gap: var(--space-2);
            align-items: center;
            z-index: 1000;
            border: 1px solid var(--gray-200);
        }

        .demo-controls h4 {
            font-size: var(--font-size-xs);
            color: var(--gray-500);
            margin-right: var(--space-2);
            white-space: nowrap;
        }

        .state-btn {
            padding: var(--space-2) var(--space-3);
            border: 1px solid var(--gray-300);
            background: var(--white);
            border-radius: var(--radius-sm);
            font-size: var(--font-size-xs);
            cursor: pointer;
            transition: var(--transition-normal);
            color: var(--gray-600);
        }

        .state-btn:hover {
            background: var(--gray-50);
            border-color: var(--primary-color);
        }

        .state-btn.active {
            background: var(--primary-color);
            color: var(--white);
            border-color: var(--primary-color);
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .container {
                padding: var(--space-4);
            }

            .session-header {
                flex-direction: column;
                align-items: flex-start;
                gap: var(--space-3);
            }

            .session-title {
                font-size: var(--font-size-2xl);
            }

            .video-container {
                grid-template-columns: 1fr;
            }

            .content-grid {
                grid-template-columns: 1fr;
            }

            .speakers-grid {
                grid-template-columns: 1fr;
            }

            .speaker-card {
                flex-direction: column;
                text-align: center;
            }

            .demo-controls {
                position: relative;
                bottom: auto;
                right: auto;
                margin-top: var(--space-8);
                justify-content: center;
                flex-wrap: wrap;
            }

            .demo-controls h4 {
                width: 100%;
                text-align: center;
                margin-bottom: var(--space-2);
            }

            .primary-actions, .post-actions {
                justify-content: center;
            }

            .btn-primary, .btn-secondary {
                flex: 1;
                justify-content: center;
                min-width: 140px;
            }
        }

        @media (max-width: 480px) {
            .session-details {
                grid-template-columns: 1fr;
            }

            .video-grid {
                grid-template-columns: 1fr;
            }

            .emoji-reactions {
                justify-content: center;
            }
        }

        /* Loading Animation Styles */
        .loading-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(255, 255, 255, 0.95);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            z-index: 9999;
            transition: opacity 0.3s ease;
        }

        .loading-spinner {
            width: 50px;
            height: 50px;
            border: 4px solid var(--gray-200);
            border-top: 4px solid var(--primary-color);
            border-radius: 50%;
            animation: spin 1s linear infinite;
            margin-bottom: var(--space-4);
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        .loading-overlay p {
            color: var(--gray-600);
            font-weight: 500;
        }

        /* Enhanced Live Player Styles */
        .live-player-container {
            width: 100%;
            height: 100%;
            position: relative;
            overflow: hidden;
        }

        .live-stream-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 50%, #f093fb 100%);
            background-size: 200% 200%;
            animation: gradientShift 8s ease-in-out infinite;
            width: 100%;
            height: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            position: relative;
            color: white;
            padding: var(--space-6);
        }

        @keyframes gradientShift {
            0%, 100% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
        }

        .live-indicator {
            position: absolute;
            top: var(--space-4);
            left: var(--space-4);
            background: rgba(220, 38, 38, 0.9);
            padding: var(--space-1) var(--space-3);
            border-radius: var(--radius-full);
            font-size: var(--font-size-xs);
            font-weight: 700;
            display: flex;
            align-items: center;
            gap: var(--space-1);
            box-shadow: var(--shadow-lg);
        }

        .live-dot {
            width: 8px;
            height: 8px;
            background: white;
            border-radius: 50%;
            animation: pulse 1.5s ease-in-out infinite;
        }

        .live-content {
            text-align: center;
            z-index: 2;
        }

        .live-icon {
            font-size: 4rem;
            margin-bottom: var(--space-4);
            opacity: 0.9;
            animation: float 3s ease-in-out infinite;
        }

        .live-content h3 {
            font-size: var(--font-size-2xl);
            font-weight: 700;
            margin-bottom: var(--space-2);
        }

        .live-content p {
            font-size: var(--font-size-lg);
            opacity: 0.9;
            margin-bottom: var(--space-4);
        }

        .viewer-count {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: var(--space-2);
            font-size: var(--font-size-base);
            opacity: 0.8;
        }

        .live-controls {
            position: absolute;
            bottom: var(--space-4);
            right: var(--space-4);
            display: flex;
            gap: var(--space-2);
        }

        .live-control-btn {
            background: rgba(255, 255, 255, 0.2);
            border: 1px solid rgba(255, 255, 255, 0.3);
            color: white;
            padding: var(--space-2);
            border-radius: var(--radius-sm);
            cursor: pointer;
            transition: var(--transition-normal);
            backdrop-filter: blur(10px);
        }

        .live-control-btn:hover {
            background: rgba(255, 255, 255, 0.3);
            transform: translateY(-2px);
        }

        /* New Message Animation */
        .new-message {
            background: rgba(99, 102, 241, 0.1);
            border-left: 4px solid var(--primary-color);
            padding: var(--space-2) var(--space-3);
            margin: var(--space-2) 0;
            border-radius: var(--radius-sm);
            animation: slideIn 0.5s ease-out;
        }

        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateX(20px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        /* Completion Stats Styles */
        .completion-stats {
            background: linear-gradient(135deg, #10b981, #059669);
            color: white;
            border-radius: var(--radius-lg);
            padding: var(--space-6);
            margin-bottom: var(--space-6);
            animation: slideDown 0.6s ease-out;
        }

        @keyframes slideDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .stats-header {
            text-align: center;
            margin-bottom: var(--space-5);
        }

        .stats-header h3 {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: var(--space-2);
            font-size: var(--font-size-xl);
            font-weight: 600;
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: var(--space-4);
        }

        .stat-item {
            text-align: center;
            background: rgba(255, 255, 255, 0.1);
            padding: var(--space-4);
            border-radius: var(--radius-md);
            backdrop-filter: blur(10px);
        }

        .stat-number {
            display: block;
            font-size: var(--font-size-2xl);
            font-weight: 700;
            margin-bottom: var(--space-1);
        }

        .stat-label {
            font-size: var(--font-size-sm);
            opacity: 0.9;
        }

        /* Enhanced Button Animations */
        .state-btn {
            position: relative;
            overflow: hidden;
        }

        .state-btn::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.3), transparent);
            transition: left 0.5s;
        }

        .state-btn:hover::before {
            left: 100%;
        }

        .state-btn.active {
            position: relative;
            box-shadow: 0 0 20px rgba(99, 102, 241, 0.4);
        }

        .state-btn.active::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, transparent, rgba(255, 255, 255, 0.1), transparent);
            animation: shimmer 2s infinite;
        }

        @keyframes shimmer {
            0% { transform: translateX(-100%); }
            100% { transform: translateX(100%); }
        }

        /* Interactive Panel Enhancements */
        .interactive-panel.live-active {
            border: 2px solid var(--primary-color);
            box-shadow: 0 0 30px rgba(99, 102, 241, 0.2);
        }

        /* Poll Results Animation */
        .poll-option.results {
            position: relative;
            overflow: hidden;
        }

        .poll-result-bar {
            position: absolute;
            left: 0;
            top: 0;
            height: 100%;
            background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));
            opacity: 0.2;
            transition: width 1s ease-out;
        }

        /* Enhanced Transitions */
        .section-transition {
            transform: translateY(20px);
            opacity: 0;
            transition: all 0.6s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .section-transition.visible {
            transform: translateY(0);
            opacity: 1;
        }

        /* Focus styles for accessibility */
        *:focus {
            outline: 2px solid var(--primary-color);
            outline-offset: 2px;
        }

        /* Animation for state transitions */
        .fade-in {
            animation: fadeIn 0.5s ease-in;
        }

        .fade-out {
            animation: fadeOut 0.3s ease-out;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeOut {
            from {
                opacity: 1;
                transform: translateY(0);
            }
            to {
                opacity: 0;
                transform: translateY(-20px);
            }
