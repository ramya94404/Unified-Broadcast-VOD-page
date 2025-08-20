<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unified Session Experience</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <div class="container">
        <!-- Header -->
        <header class="session-header">
            <div class="breadcrumb">
                <span>Salesforce+</span>
                <i class="fas fa-chevron-right"></i>
                <span>Dreamforce 2025</span>
                <i class="fas fa-chevron-right"></i>
                <span>AI & Innovation Track</span>
            </div>
            <div class="session-status">
                <span class="status-indicator" id="statusIndicator">Pre-Session</span>
            </div>
        </header>

        <!-- Main Content -->
        <main class="main-content">
            <!-- Session Info Section -->
            <section class="session-info">
                <div class="session-meta">
                    <div class="session-type">
                        <span class="type-badge virtual" id="sessionType">Virtual Session</span>
                        <button class="toggle-type" id="toggleType">Switch to In-Person View</button>
                    </div>
                    <h1 class="session-title">Building the Future with AI: Advanced Prompt Engineering and Agent Workflows</h1>
                    <p class="session-description">
                        Discover how to leverage advanced AI techniques to build intelligent agents and optimize prompt engineering workflows. 
                        Learn practical strategies for implementing AI solutions that scale across enterprise environments and drive real business outcomes.
                    </p>
                </div>

                <div class="session-details">
                    <div class="detail-item">
                        <i class="fas fa-calendar"></i>
                        <div>
                            <strong>Date & Time</strong>
                            <span>March 15, 2025 • 2:00 PM - 3:00 PM PST</span>
                        </div>
                    </div>
                    <div class="detail-item location-info">
                        <i class="fas fa-map-marker-alt"></i>
                        <div>
                            <strong>Location</strong>
                            <span id="locationText">Virtual Event Platform</span>
                        </div>
                    </div>
                    <div class="detail-item">
                        <i class="fas fa-users"></i>
                        <div>
                            <strong>Capacity</strong>
                            <span id="capacityText">Unlimited Virtual Seats</span>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Video Player Section (Hidden in pre-session) -->
            <section class="video-section" id="videoSection" style="display: none;">
                <div class="video-player">
                    <div class="kaltura-placeholder">
                        <i class="fas fa-play-circle"></i>
                        <p>Live Stream Starting Soon...</p>
                    </div>
                </div>
                
                <!-- Interactive Features (Live State Only) -->
                <div class="interactive-panel" id="interactivePanel">
                    <div class="chat-section">
                        <h3>Live Chat</h3>
                        <div class="chat-messages">
                            <div class="message">
                                <strong>Sarah Chen:</strong> Excited for this session! 🚀
                            </div>
                            <div class="message">
                                <strong>Marcus Williams:</strong> Great topic for enterprise AI
                            </div>
                        </div>
                        <div class="chat-input">
                            <input type="text" placeholder="Type your message...">
                            <button><i class="fas fa-paper-plane"></i></button>
                        </div>
                    </div>
                    
                    <div class="engagement-tools">
                        <div class="emoji-reactions">
                            <button class="emoji-btn">👍</button>
                            <button class="emoji-btn">❤️</button>
                            <button class="emoji-btn">🎉</button>
                            <button class="emoji-btn">👏</button>
                        </div>
                        <div class="poll-section" style="display: none;">
                            <h4>Live Poll</h4>
                            <p>What's your primary use case for AI in your organization?</p>
                            <div class="poll-options">
                                <button class="poll-option">Customer Service</button>
                                <button class="poll-option">Sales Automation</button>
                                <button class="poll-option">Data Analytics</button>
                                <button class="poll-option">Content Creation</button>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Action Buttons -->
            <section class="action-section">
                <div class="primary-actions" id="primaryActions">
                    <button class="btn-primary reserve-btn">
                        <i class="fas fa-calendar-plus"></i>
                        Reserve Spot
                    </button>
                    <button class="btn-secondary">
                        <i class="fas fa-heart"></i>
                        Add to Favorites
                    </button>
                    <button class="btn-secondary">
                        <i class="fas fa-calendar-check"></i>
                        Add to Calendar
                    </button>
                </div>
                
                <div class="post-actions" id="postActions" style="display: none;">
                    <button class="btn-primary">
                        <i class="fas fa-play"></i>
                        Watch Recording
                    </button>
                    <button class="btn-secondary">
                        <i class="fas fa-download"></i>
                        Download Materials
                    </button>
                    <button class="btn-secondary">
                        <i class="fas fa-share"></i>
                        Share Session
                    </button>
                </div>
            </section>

            <!-- Speaker Information -->
            <section class="speakers-section">
                <h2>Speakers</h2>
                <div class="speakers-grid">
                    <div class="speaker-card">
                        <div class="speaker-avatar">
                            <img src="data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iODAiIGhlaWdodD0iODAiIHZpZXdCb3g9IjAgMCA4MCA4MCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGNpcmNsZSBjeD0iNDAiIGN5PSI0MCIgcj0iNDAiIGZpbGw9IiM2MzY2RjEiLz4KPHRleHQgeD0iNDAiIHk9IjQ4IiB0ZXh0LWFuY2hvcj0ibWlkZGxlIiBmaWxsPSJ3aGl0ZSIgZm9udC1mYW1pbHk9IkludGVyIiBmb250LXNpemU9IjI0IiBmb250LXdlaWdodD0iNjAwIj5EUjwvdGV4dD4KPHN2Zz4=" alt="Dr. Raj Patel">
                        </div>
                        <div class="speaker-info">
                            <h3>Dr. Raj Patel</h3>
                            <p class="speaker-title">Chief AI Officer, Salesforce</p>
                            <p class="speaker-bio">Leading AI innovation with 15+ years in machine learning and enterprise AI solutions.</p>
                            <div class="speaker-social">
                                <a href="#"><i class="fab fa-linkedin"></i></a>
                                <a href="#"><i class="fab fa-twitter"></i></a>
                            </div>
                        </div>
                    </div>
                    
                    <div class="speaker-card">
                        <div class="speaker-avatar">
                            <img src="data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iODAiIGhlaWdodD0iODAiIHZpZXdCb3g9IjAgMCA4MCA4MCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGNpcmNsZSBjeD0iNDAiIGN5PSI0MCIgcj0iNDAiIGZpbGw9IiNGRjY1ODQiLz4KPHRleHQgeD0iNDAiIHk9IjQ4IiB0ZXh0LWFuY2hvcj0ibWlkZGxlIiBmaWxsPSJ3aGl0ZSIgZm9udC1mYW1pbHk9IkludGVyIiBmb250LXNpemU9IjI0IiBmb250LXdlaWdodD0iNjAwIj5BTTwvdGV4dD4KPHN2Zz4=" alt="Alex Morgan">
                        </div>
                        <div class="speaker-info">
                            <h3>Alex Morgan</h3>
                            <p class="speaker-title">Senior Product Manager, AI Platform</p>
                            <p class="speaker-bio">Product leader focused on democratizing AI tools for developers and business users.</p>
                            <div class="speaker-social">
                                <a href="#"><i class="fab fa-linkedin"></i></a>
                                <a href="#"><i class="fab fa-twitter"></i></a>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Post-Session Content (Hidden initially) -->
            <section class="post-content" id="postContent" style="display: none;">
                <div class="content-grid">
                    <div class="transcript-section">
                        <h3><i class="fas fa-file-text"></i> Session Transcript</h3>
                        <div class="transcript-content">
                            <p><strong>Dr. Raj Patel:</strong> Welcome everyone to our session on advanced AI techniques. Today we'll explore how prompt engineering...</p>
                            <p><strong>Alex Morgan:</strong> Thanks Raj. Let's start with the fundamental principles that make AI agents effective in enterprise environments...</p>
                            <button class="expand-btn">View Full Transcript</button>
                        </div>
                    </div>
                    
                    <div class="materials-section">
                        <h3><i class="fas fa-download"></i> Session Materials</h3>
                        <div class="materials-list">
                            <a href="#" class="material-item">
                                <i class="fas fa-file-pdf"></i>
                                <span>AI Strategy Playbook (PDF)</span>
                            </a>
                            <a href="#" class="material-item">
                                <i class="fas fa-code"></i>
                                <span>Code Examples & Templates</span>
                            </a>
                            <a href="#" class="material-item">
                                <i class="fas fa-chart-line"></i>
                                <span>Implementation Framework</span>
                            </a>
                        </div>
                    </div>
                    
                    <div class="summary-section">
                        <h3><i class="fas fa-lightbulb"></i> Key Takeaways</h3>
                        <ul class="takeaways-list">
                            <li>Implement structured prompt engineering workflows for consistent AI outputs</li>
                            <li>Design agent architectures that scale across enterprise environments</li>
                            <li>Establish governance frameworks for responsible AI deployment</li>
                            <li>Leverage feedback loops to continuously improve AI performance</li>
                        </ul>
                    </div>
                </div>
                
                <div class="related-content">
                    <h3>Related Sessions & Videos</h3>
                    <div class="video-grid">
                        <div class="video-card">
                            <div class="video-thumbnail">
                                <i class="fab fa-youtube"></i>
                            </div>
                            <div class="video-info">
                                <h4>AI Ethics in Practice</h4>
                                <p>Implementing responsible AI frameworks</p>
                                <span class="video-duration">45 min</span>
                            </div>
                        </div>
                        
                        <div class="video-card">
                            <div class="video-thumbnail">
                                <i class="fas fa-play"></i>
                            </div>
                            <div class="video-info">
                                <h4>Advanced Machine Learning</h4>
                                <p>Deep dive into ML model optimization</p>
                                <span class="video-duration">38 min</span>
                            </div>
                        </div>
                        
                        <div class="video-card">
                            <div class="video-thumbnail">
                                <i class="fab fa-youtube"></i>
                            </div>
                            <div class="video-info">
                                <h4>Future of AI Development</h4>
                                <p>Trends and predictions for 2025</p>
                                <span class="video-duration">42 min</span>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <!-- State Control Demo -->
            <div class="demo-controls">
                <h4>Demo State Controls:</h4>
                <button class="state-btn active" data-state="pre">Pre-Session</button>
                <button class="state-btn" data-state="live">Live Session</button>
                <button class="state-btn" data-state="post">Post-Session</button>
            </div>
        </main>
    </div>

    <style>
        /* Reset and Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            line-height: 1.6;
            color: #1f2937;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background: white;
            min-height: 100vh;
            box-shadow: 0 0 30px rgba(0,0,0,0.1);
        }

        /* Header Styles */
        .session-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding-bottom: 20px;
            border-bottom: 1px solid #e5e7eb;
            margin-bottom: 30px;
        }

        .breadcrumb {
            display: flex;
            align-items: center;
            gap: 8px;
            color: #6b7280;
            font-size: 14px;
        }

        .breadcrumb i {
            font-size: 12px;
        }

        .session-status {
            display: flex;
            align-items: center;
        }

        .status-indicator {
            padding: 6px 16px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: 500;
            background: #dbeafe;
            color: #1e40af;
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
            0%, 100% { opacity: 1; }
            50% { opacity: 0.7; }
        }

        /* Session Info Styles */
        .session-info {
            margin-bottom: 30px;
        }

        .session-meta {
            margin-bottom: 25px;
        }

        .session-type {
            display: flex;
            align-items: center;
            gap: 15px;
            margin-bottom: 15px;
        }

        .type-badge {
            padding: 4px 12px;
            border-radius: 15px;
            font-size: 12px;
            font-weight: 500;
            text-transform: uppercase;
            letter-spacing: 0.5px;
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
            border: 1px solid #d1d5db;
            padding: 6px 12px;
            border-radius: 6px;
            font-size: 12px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .toggle-type:hover {
            background: #f9fafb;
            border-color: #9ca3af;
        }

        .session-title {
            font-size: 2rem;
            font-weight: 700;
            margin-bottom: 15px;
            color: #111827;
            line-height: 1.3;
        }

        .session-description {
            font-size: 1.1rem;
            color: #6b7280;
            line-height: 1.7;
        }

        .session-details {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .detail-item {
            display: flex;
            align-items: flex-start;
            gap: 12px;
        }

        .detail-item i {
            color: #6366f1;
            font-size: 18px;
            margin-top: 2px;
            min-width: 20px;
        }

        .detail-item strong {
            display: block;
            margin-bottom: 2px;
            color: #374151;
        }

        .detail-item span {
            color: #6b7280;
            font-size: 14px;
        }

        /* Video Section Styles */
        .video-section {
            margin-bottom: 30px;
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 30px;
        }

        .video-player {
            background: #000;
            border-radius: 12px;
            aspect-ratio: 16/9;
            overflow: hidden;
            position: relative;
        }

        .kaltura-placeholder {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100%;
            color: white;
            gap: 15px;
        }

        .kaltura-placeholder i {
            font-size: 4rem;
            opacity: 0.7;
        }

        .kaltura-placeholder p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        /* Interactive Panel Styles */
        .interactive-panel {
            background: #f9fafb;
            border-radius: 12px;
            padding: 20px;
            height: fit-content;
        }

        .chat-section h3 {
            margin-bottom: 15px;
            font-size: 1.1rem;
            color: #374151;
        }

        .chat-messages {
            background: white;
            border-radius: 8px;
            padding: 15px;
            margin-bottom: 15px;
            height: 200px;
            overflow-y: auto;
            border: 1px solid #e5e7eb;
        }

        .message {
            margin-bottom: 10px;
            padding: 8px 0;
            border-bottom: 1px solid #f3f4f6;
            font-size: 14px;
        }

        .message strong {
            color: #6366f1;
        }

        .chat-input {
            display: flex;
            gap: 10px;
        }

        .chat-input input {
            flex: 1;
            padding: 10px 12px;
            border: 1px solid #d1d5db;
            border-radius: 6px;
            font-size: 14px;
        }

        .chat-input button {
            padding: 10px 15px;
            background: #6366f1;
            color: white;
            border: none;
            border-radius: 6px;
            cursor: pointer;
        }

        .engagement-tools {
            margin-top: 20px;
        }

        .emoji-reactions {
            display: flex;
            gap: 8px;
            margin-bottom: 20px;
        }

        .emoji-btn {
            background: white;
            border: 1px solid #e5e7eb;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            font-size: 18px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .emoji-btn:hover {
            transform: scale(1.1);
            border-color: #6366f1;
        }

        .poll-section {
            background: white;
            border-radius: 8px;
            padding: 15px;
            border: 1px solid #e5e7eb;
        }

        .poll-section h4 {
            margin-bottom: 10px;
            color: #374151;
        }

        .poll-section p {
            margin-bottom: 15px;
            color: #6b7280;
            font-size: 14px;
        }

        .poll-options {
            display: grid;
            gap: 8px;
        }

        .poll-option {
            padding: 10px;
            background: #f9fafb;
            border: 1px solid #e5e7eb;
            border-radius: 6px;
            text-align: left;
            cursor: pointer;
            transition: all 0.3s ease;
            font-size: 14px;
        }

        .poll-option:hover {
            background: #e0e7ff;
            border-color: #6366f1;
        }

        /* Action Section Styles */
        .action-section {
            margin-bottom: 40px;
        }

        .primary-actions, .post-actions {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
        }

        .btn-primary, .btn-secondary {
            display: flex;
            align-items: center;
            gap: 8px;
            padding: 12px 24px;
            border-radius: 8px;
            font-weight: 500;
            text-decoration: none;
            transition: all 0.3s ease;
            cursor: pointer;
            border: none;
            font-size: 14px;
        }

        .btn-primary {
            background: linear-gradient(135deg, #6366f1, #8b5cf6);
            color: white;
        }

        .btn-primary:hover {
            background: linear-gradient(135deg, #5856eb, #7c3aed);
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(99, 102, 241, 0.3);
        }

        .btn-secondary {
            background: white;
            color: #374151;
            border: 1px solid #d1d5db;
        }

        .btn-secondary:hover {
            background: #f9fafb;
            border-color: #9ca3af;
        }

        /* Speaker Section Styles */
        .speakers-section {
            margin-bottom: 40px;
        }

        .speakers-section h2 {
            margin-bottom: 25px;
            font-size: 1.5rem;
            color: #111827;
        }

        .speakers-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
        }

        .speaker-card {
            background: #f9fafb;
            border-radius: 12px;
            padding: 25px;
            display: flex;
            gap: 20px;
            transition: all 0.3s ease;
        }

        .speaker-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
        }

        .speaker-avatar img {
            width: 80px;
            height: 80px;
            border-radius: 50%;
        }

        .speaker-info h3 {
            margin-bottom: 5px;
            color: #111827;
        }

        .speaker-title {
            color: #6366f1;
            font-weight: 500;
            margin-bottom: 8px;
            font-size: 14px;
        }

        .speaker-bio {
            color: #6b7280;
            font-size: 14px;
            margin-bottom: 15px;
        }

        .speaker-social {
            display: flex;
            gap: 10px;
        }

        .speaker-social a {
            color: #6b7280;
            font-size: 18px;
            transition: color 0.3s ease;
        }

        .speaker-social a:hover {
            color: #6366f1;
        }

        /* Post Content Styles */
        .post-content {
            margin-bottom: 40px;
        }

        .content-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
            margin-bottom: 40px;
        }

        .transcript-section, .materials-section, .summary-section {
            background: #f9fafb;
            border-radius: 12px;
            padding: 25px;
        }

        .transcript-section {
            grid-column: 1 / -1;
        }

        .transcript-section h3, .materials-section h3, .summary-section h3 {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 15px;
            color: #374151;
        }

        .transcript-content p {
            margin-bottom: 10px;
            color: #6b7280;
            font-size: 14px;
        }

        .expand-btn {
            background: #6366f1;
            color: white;
            border: none;
            padding: 8px 16px;
            border-radius: 6px;
            cursor: pointer;
            font-size: 12px;
            margin-top: 15px;
        }

        .materials-list {
            display: flex;
            flex-direction: column;
            gap: 12px;
        }

        .material-item {
            display: flex;
            align-items: center;
            gap: 12px;
            padding: 12px;
            background: white;
            border-radius: 8px;
            text-decoration: none;
            color: #374151;
            transition: all 0.3s ease;
        }

        .material-item:hover {
            background: #e0e7ff;
            color: #6366f1;
        }

        .takeaways-list {
            list-style: none;
        }

        .takeaways-list li {
            padding: 8px 0;
            padding-left: 20px;
            position: relative;
            color: #6b7280;
            font-size: 14px;
        }

        .takeaways-list li::before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #10b981;
            font-weight: bold;
        }

        .related-content h3 {
            margin-bottom: 20px;
            color: #374151;
        }

        .video-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .video-card {
            background: #f9fafb;
            border-radius: 12px;
            padding: 20px;
            display: flex;
            gap: 15px;
            transition: all 0.3s ease;
        }

        .video-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(0,0,0,0.1);
        }

        .video-thumbnail {
            width: 60px;
            height: 45px;
            background: #6366f1;
            border-radius: 6px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 20px;
        }

        .video-info h4 {
            margin-bottom: 5px;
            color: #374151;
            font-size: 14px;
        }

        .video-info p {
            color: #6b7280;
            font-size: 12px;
            margin-bottom: 5px;
        }

        .video-duration {
            color: #9ca3af;
            font-size: 11px;
        }

        /* Demo Controls */
        .demo-controls {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: white;
            padding: 15px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.1);
            display: flex;
            gap: 10px;
            align-items: center;
            z-index: 1000;
        }

        .demo-controls h4 {
            font-size: 12px;
            color: #6b7280;
            margin-right: 10px;
        }

        .state-btn {
            padding: 6px 12px;
            border: 1px solid #
