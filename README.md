<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>H.O.R.D.E.R.S Pitch Deck</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif;
            line-height: 1.6;
            color: #e5e7eb;
        }
        
        .page {
            width: 210mm;
            min-height: 297mm;
            margin: 0 auto;
            background: linear-gradient(135deg, #1f2937 0%, #000000 50%, #1f2937 100%);
            padding: 60px;
            page-break-after: always;
            position: relative;
        }
        
        .page:last-child {
            page-break-after: auto;
        }
        
        h1 {
            font-size: 48px;
            color: #22d3ee;
            margin-bottom: 20px;
            border-bottom: 3px solid rgba(34, 211, 238, 0.3);
            padding-bottom: 20px;
        }
        
        h2 {
            font-size: 32px;
            color: #22d3ee;
            margin-bottom: 15px;
        }
        
        h3 {
            font-size: 24px;
            color: #22d3ee;
            margin-bottom: 10px;
        }
        
        h4 {
            font-size: 20px;
            color: #22d3ee;
            margin-bottom: 10px;
        }
        
        p {
            margin-bottom: 15px;
            font-size: 16px;
        }
        
        ul {
            list-style: none;
            margin-bottom: 20px;
        }
        
        li {
            margin-bottom: 12px;
            padding-left: 25px;
            position: relative;
        }
        
        li:before {
            content: "▸";
            position: absolute;
            left: 0;
            color: #22d3ee;
        }
        
        .subtitle {
            font-size: 28px;
            color: #9ca3af;
            margin-bottom: 40px;
        }
        
        .center {
            text-align: center;
        }
        
        .grid-2 {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 25px;
            margin-bottom: 25px;
        }
        
        .grid-3 {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            margin-bottom: 30px;
        }
        
        .box {
            background: rgba(31, 41, 55, 0.8);
            padding: 25px;
            border-radius: 8px;
            border: 1px solid rgba(34, 211, 238, 0.2);
        }
        
        .stat-box {
            background: rgba(8, 51, 68, 0.3);
            padding: 25px;
            border-radius: 8px;
            text-align: center;
        }
        
        .stat-number {
            font-size: 42px;
            font-weight: bold;
            color: #22d3ee;
            margin-bottom: 10px;
        }
        
        .stat-label {
            font-size: 14px;
            color: #9ca3af;
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        
        th, td {
            padding: 12px;
            text-align: left;
            border-bottom: 1px solid #374151;
        }
        
        th {
            color: #22d3ee;
            font-weight: bold;
        }
        
        .check {
            color: #22d3ee;
        }
        
        .cross {
            color: #4b5563;
        }
        
        .timeline-item {
            display: flex;
            margin-bottom: 20px;
            align-items: flex-start;
        }
        
        .timeline-badge {
            background: #0e7490;
            color: white;
            padding: 8px 16px;
            border-radius: 6px;
            font-weight: bold;
            font-size: 14px;
            margin-right: 20px;
            white-space: nowrap;
        }
        
        .timeline-badge.purple {
            background: #7c3aed;
        }
        
        .timeline-badge.yellow {
            background: #eab308;
            color: black;
        }
        
        .timeline-content h4 {
            margin-bottom: 5px;
        }
        
        .timeline-content p {
            font-size: 14px;
            color: #9ca3af;
            margin: 0;
        }
        
        .italic {
            font-style: italic;
            color: #9ca3af;
            font-size: 14px;
        }
        
        .feature-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
        }
        
        .feature-item {
            background: linear-gradient(90deg, rgba(8, 51, 68, 0.5) 0%, transparent 100%);
            padding: 15px;
            border-radius: 6px;
        }
        
        .numbered-item {
            display: flex;
            align-items: center;
            background: rgba(31, 41, 55, 0.8);
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 15px;
        }
        
        .number {
            font-size: 32px;
            font-weight: bold;
            color: #22d3ee;
            margin-right: 20px;
            min-width: 50px;
        }
        
        .highlight-box {
            background: linear-gradient(90deg, rgba(8, 51, 68, 0.5) 0%, transparent 100%);
            padding: 30px;
            border-radius: 8px;
            margin-bottom: 25px;
        }
        
        .contact-info {
            font-size: 24px;
            margin: 15px 0;
        }
        
        .contact-email {
            color: #22d3ee;
        }
        
        .quote {
            margin-top: 60px;
            color: #6b7280;
            font-style: italic;
            font-size: 14px;
        }
        
        @media print {
            body {
                print-color-adjust: exact;
                -webkit-print-color-adjust: exact;
            }
            
            .page {
                margin: 0;
                page-break-after: always;
            }
        }
    </style>
</head>
<body>

<!-- Slide 1: Title -->
<div class="page">
    <div class="center" style="padding-top: 120px;">
        <h1 style="font-size: 72px; border: none; margin-bottom: 30px;">H.O.R.D.E.R.S</h1>
        <p class="subtitle">Hazardous Object Recovery, Discovery, & Extermination Retrieval Squad</p>
        <p style="font-size: 28px; color: #9ca3af; margin: 40px 0;">The infinite procedural sci-fi FPS roguelike</p>
        <p style="font-size: 20px; color: #9ca3af;">Doogan Inc Studios</p>
    </div>
</div>

<!-- Slide 2: The Problem -->
<div class="page">
    <h1>The Problem</h1>
    <p style="font-size: 22px; color: #d1d5db; margin-bottom: 30px;">Modern roguelikes are becoming formulaic:</p>
    <ul style="font-size: 18px;">
        <li>Limited upgrade systems with predetermined builds</li>
        <li>Shallow procedural generation that feels repetitive</li>
        <li>Disconnected gameplay loops between combat and exploration</li>
        <li>Players crave truly chaotic, experimental sandbox experiences</li>
    </ul>
</div>

<!-- Slide 3: The Solution -->
<div class="page">
    <h1>The Solution</h1>
    <p style="font-size: 22px; color: #22d3ee; margin-bottom: 30px;">Infinite modular chaos meets retro FPS action</p>
    <div class="grid-2">
        <div class="box">
            <h3>Infinite Crafting™</h3>
            <p style="font-size: 14px;">Combine ANY artifact with ANY DNA strain for emergent builds</p>
        </div>
        <div class="box">
            <h3>True Procedural</h3>
            <p style="font-size: 14px;">Ships, enemies, artifacts, encounters—all unique every run</p>
        </div>
        <div class="box">
            <h3>Full Immersion</h3>
            <p style="font-size: 14px;">Pilot ships, maintain systems via DOS terminal, explore space</p>
        </div>
        <div class="box">
            <h3>Personality</h3>
            <p style="font-size: 14px;">B.U.D.D.Y AI brings sarcastic life to the loot grind</p>
        </div>
    </div>
</div>

<!-- Slide 4: Market Opportunity -->
<div class="page">
    <h1>Market Opportunity</h1>
    <div class="grid-3">
        <div class="stat-box">
            <div class="stat-number">$4.9B</div>
            <div class="stat-label">Indie Steam revenue 2024</div>
        </div>
        <div class="stat-box">
            <div class="stat-number">48%</div>
            <div class="stat-label">Share of Steam revenue</div>
        </div>
        <div class="stat-box">
            <div class="stat-number">6-12%</div>
            <div class="stat-label">Roguelike CAGR growth</div>
        </div>
    </div>
    <p style="font-size: 18px; margin: 30px 0;">Target audience: Fans of Risk of Rain 2, Deep Rock Galactic, DOOM, Binding of Isaac, and No Man's Sky who want deeper experimentation and retro vibes</p>
    <p class="italic">Indie games generated nearly $4 billion on Steam in 2024, with roguelikes being one of the fastest-growing genres</p>
</div>

<!-- Slide 5: Unique Gameplay Loop -->
<div class="page">
    <h1>Unique Gameplay Loop</h1>
    <div class="numbered-item">
        <div class="number">1</div>
        <div>
            <h4>Pilot & Dock</h4>
            <p style="font-size: 14px; color: #9ca3af;">Manual ship piloting, dogfights, and docking onto derelicts</p>
        </div>
    </div>
    <div class="numbered-item">
        <div class="number">2</div>
        <div>
            <h4>Explore & Exterminate</h4>
            <p style="font-size: 14px; color: #9ca3af;">FPS combat through procedural dungeons with retro horror vibes</p>
        </div>
    </div>
    <div class="numbered-item">
        <div class="number">3</div>
        <div>
            <h4>Collect & Craft</h4>
            <p style="font-size: 14px; color: #9ca3af;">Gather cursed artifacts and alien DNA for modular upgrades</p>
        </div>
    </div>
    <div class="numbered-item">
        <div class="number">4</div>
        <div>
            <h4>Trade & Maintain</h4>
            <p style="font-size: 14px; color: #9ca3af;">Barter with B.U.D.D.Y, repair ship via DOS terminal, repeat</p>
        </div>
    </div>
</div>

<!-- Slide 6: Key Features -->
<div class="page">
    <h1>Key Features</h1>
    <div class="feature-grid">
        <div>
            <div class="feature-item">
                <h4>∞ Procedural Generation</h4>
                <p style="font-size: 14px; color: #9ca3af;">Ships, enemies, artifacts, encounters</p>
            </div>
            <div class="feature-item">
                <h4>Modular Crafting</h4>
                <p style="font-size: 14px; color: #9ca3af;">Plug-and-play artifact system</p>
            </div>
            <div class="feature-item">
                <h4>Space Combat</h4>
                <p style="font-size: 14px; color: #9ca3af;">Dogfights, manual piloting, autopilot</p>
            </div>
            <div class="feature-item">
                <h4>Retro FPS Combat</h4>
                <p style="font-size: 14px; color: #9ca3af;">DOOM meets Time Crisis</p>
            </div>
        </div>
        <div>
            <div class="feature-item">
                <h4>B.U.D.D.Y AI</h4>
                <p style="font-size: 14px; color: #9ca3af;">Sarcastic trading companion</p>
            </div>
            <div class="feature-item">
                <h4>DOS Ship Terminal</h4>
                <p style="font-size: 14px; color: #9ca3af;">80s-style maintenance system</p>
            </div>
            <div class="feature-item">
                <h4>High Stakes</h4>
                <p style="font-size: 14px; color: #9ca3af;">Lose your ship = lose everything</p>
            </div>
            <div class="feature-item">
                <h4>Deep Replayability</h4>
                <p style="font-size: 14px; color: #9ca3af;">Every run is completely unique</p>
            </div>
        </div>
    </div>
</div>

<!-- Slide 7: Competition -->
<div class="page">
    <h1>Competition & Differentiation</h1>
    <table>
        <thead>
            <tr>
                <th>Feature</th>
                <th class="center" style="text-align: center;">H.O.R.D.E.R.S</th>
                <th style="text-align: center;">Risk of Rain 2</th>
                <th style="text-align: center;">Deep Rock</th>
                <th style="text-align: center;">No Man's Sky</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Infinite Crafting</td>
                <td class="check" style="text-align: center;">✓</td>
                <td class="cross" style="text-align: center;">✗</td>
                <td class="cross" style="text-align: center;">✗</td>
                <td style="text-align: center;">~</td>
            </tr>
            <tr>
                <td>FPS Combat</td>
                <td class="check" style="text-align: center;">✓</td>
                <td style="text-align: center;">~</td>
                <td class="check" style="text-align: center;">✓</td>
                <td style="text-align: center;">~</td>
            </tr>
            <tr>
                <td>Ship Piloting</td>
                <td class="check" style="text-align: center;">✓</td>
                <td class="cross" style="text-align: center;">✗</td>
                <td class="cross" style="text-align: center;">✗</td>
                <td class="check" style="text-align: center;">✓</td>
            </tr>
            <tr>
                <td>Roguelike Loop</td>
                <td class="check" style="text-align: center;">✓</td>
                <td class="check" style="text-align: center;">✓</td>
                <td class="cross" style="text-align: center;">✗</td>
                <td class="cross" style="text-align: center;">✗</td>
            </tr>
            <tr>
                <td>Retro Horror Vibe</td>
                <td class="check" style="text-align: center;">✓</td>
                <td class="cross" style="text-align: center;">✗</td>
                <td class="cross" style="text-align: center;">✗</td>
                <td class="cross" style="text-align: center;">✗</td>
            </tr>
        </tbody>
    </table>
    <p class="center italic" style="margin-top: 30px;">We combine the best elements while adding true modular chaos</p>
</div>

<!-- Slide 8: Development Roadmap -->
<div class="page">
    <h1>Development Roadmap</h1>
    <div class="timeline-item">
        <div class="timeline-badge">2026</div>
        <div class="timeline-content">
            <h4>v0.1.0 Alpha</h4>
            <p>Initial release on Itch.io - core gameplay loop, procedural generation, basic crafting</p>
        </div>
    </div>
    <div class="timeline-item">
        <div class="timeline-badge">NEXT</div>
        <div class="timeline-content">
            <h4>v0.5.x - Planetary Exploration</h4>
            <p>Expand beyond ships to full planet surfaces</p>
        </div>
    </div>
    <div class="timeline-item">
        <div class="timeline-badge purple">TBD</div>
        <div class="timeline-content">
            <h4>v0.8.x - Multiplayer</h4>
            <p>Online/LAN/Couch co-op for 2-4 players</p>
        </div>
    </div>
    <div class="timeline-item">
        <div class="timeline-badge purple">TBD</div>
        <div class="timeline-content">
            <h4>v0.9.x - Modding Support</h4>
            <p>Community tools and mod framework</p>
        </div>
    </div>
    <div class="timeline-item">
        <div class="timeline-badge yellow">2027</div>
        <div class="timeline-content">
            <h4>v1.0 - Steam Launch</h4>
            <p>Full release when it's good and weird enough</p>
        </div>
    </div>
</div>

<!-- Slide 9: Business Model -->
<div class="page">
    <h1>Business Model</h1>
    <div class="highlight-box">
        <h3 style="margin-bottom: 20px;">Free-to-Play Development Phase</h3>
        <p>Currently free on Itch.io to build community, gather feedback, and iterate rapidly</p>
    </div>
    <div class="box">
        <h4 style="margin-bottom: 20px;">Simple, Player-First Model</h4>
        <ul style="margin-bottom: 30px;">
            <li>
                <strong>Premium purchase ($19.99-24.99)</strong><br>
                <span style="font-size: 14px; color: #9ca3af;">One-time purchase on Steam</span>
            </li>
            <li>
                <strong>Console ports</strong><br>
                <span style="font-size: 14px; color: #9ca3af;">Expanded platform reach</span>
            </li>
        </ul>
        <div style="border-top: 1px solid #374151; padding-top: 20px;">
            <p class="italic">All DLC, updates, and expansions will be free added content. No microtransactions, no season passes. Just a game that gets better over time.</p>
        </div>
    </div>
</div>

<!-- Slide 10: Traction & Community -->
<div class="page">
    <h1>Traction & Community</h1>
    <div class="grid-3">
        <div class="stat-box">
            <div class="stat-number">In Dev</div>
            <div class="stat-label">Alpha launching 2026</div>
        </div>
        <div class="stat-box">
            <div class="stat-number">Growing</div>
            <div class="stat-label">Community building</div>
        </div>
        <div class="stat-box">
            <div class="stat-number">Transparent</div>
            <div class="stat-label">Public development</div>
        </div>
    </div>
    <div class="box">
        <h4 style="margin-bottom: 15px;">Community-First Development</h4>
        <p style="margin-bottom: 20px;">Building in public with full transparency, gathering feedback at every stage to ensure I'm creating the chaotic roguelike experience players actually want.</p>
        <div style="display: flex; gap: 15px; font-size: 14px;">
            <div class="stat-box" style="padding: 10px 20px;">Instagram Active</div>
            <div class="stat-box" style="padding: 10px 20px;">Discord Coming Soon</div>
        </div>
    </div>
</div>

<!-- Slide 11: The Team -->
<div class="page">
    <h1>The Team</h1>
    <div class="center" style="margin-bottom: 40px;">
        <h2 style="margin-bottom: 10px;">Zac L</h2>
        <p style="font-size: 22px; margin-bottom: 10px;">Solo Developer</p>
        <p style="color: #9ca3af;">Doogan Inc Studios</p>
    </div>
    <div class="box">
        <h4 style="margin-bottom: 15px;">Our Philosophy</h4>
        <ul>
            <li>Developer transparency and community engagement</li>
            <li>Iterative development with player feedback</li>
            <li>Creating experiences that embrace chaos and experimentation</li>
            <li>Building games I want to play</li>
        </ul>
    </div>
</div>

<!-- Slide 12: Why Now? -->
<div class="page">
    <h1>Why Now?</h1>
    <div class="highlight-box">
        <h3 style="margin-bottom: 25px;">Perfect Market Timing</h3>
        <ul style="font-size: 16px;">
            <li style="margin-bottom: 25px;">
                <span class="number" style="display: inline; margin: 0; min-width: auto; font-size: 28px;">1</span>
                <div style="display: inline-block; vertical-align: top; width: calc(100% - 60px); margin-left: 10px;">
                    <strong>Roguelike Renaissance</strong><br>
                    <span style="font-size: 14px; color: #9ca3af;">Genre is at peak popularity with proven monetization</span>
                </div>
            </li>
            <li style="margin-bottom: 25px;">
                <span class="number" style="display: inline; margin: 0; min-width: auto; font-size: 28px;">2</span>
                <div style="display: inline-block; vertical-align: top; width: calc(100% - 60px); margin-left: 10px;">
                    <strong>Retro Aesthetic Demand</strong><br>
                    <span style="font-size: 14px; color: #9ca3af;">Players are nostalgic for PS1/N64-era visuals with modern mechanics</span>
                </div>
     </table>
<!-- Slide 14: Contact -->
<div class="page">
    <div class="center" style="padding-top: 100px;">
        <h1 style="font-size: 60px; margin-bottom: 60px;">Let's Talk</h1>
        <div style="font-size: 24px; line-height: 2;">
            <p>Zac L | Solo Developer</p>
            <p class="contact-email">zachary1101@gmail.com</p>
            <p style="font-size: 20px;">doogan-inc-studios.itch.io/horders</p>
            <p style="font-size: 16px; color: #9ca3af;">Instagram: @h.o.r.d.e.r.s</p>
        </div>
        <p class="quote" style="margin-top: 100px;">"Bring a flashlight. And maybe a bucket."</p>
    </div>
</div>

</body>
</html>
