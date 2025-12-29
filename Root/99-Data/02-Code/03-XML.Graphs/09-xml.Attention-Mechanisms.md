
```xml
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 500">
  <!-- Background -->
  <rect width="900" height="500" fill="#f8f9fa"/>
  
  <!-- Title -->
  <text x="450" y="40" font-family="Arial" font-size="24" text-anchor="middle" font-weight="bold">Attention Mechanisms: Geometric Transformations</text>
  
  <!-- Left side: Vector space visualization -->
  <g transform="translate(100, 100)">
    <rect width="250" height="300" rx="10" fill="#e3f2fd" stroke="#1565c0" stroke-width="2"/>
    <text x="125" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Before Attention</text>
    
    <!-- Vector points -->
    <circle cx="60" cy="80" r="5" fill="#1565c0"/>
    <circle cx="120" cy="100" r="5" fill="#1565c0"/>
    <circle cx="180" cy="120" r="5" fill="#1565c0"/>
    <circle cx="90" cy="160" r="5" fill="#1565c0"/>
    <circle cx="150" cy="200" r="5" fill="#1565c0"/>
    
    <!-- Token labels -->
    <text x="60" y="70" font-family="Arial" font-size="12" text-anchor="middle">token₁</text>
    <text x="120" y="90" font-family="Arial" font-size="12" text-anchor="middle">token₂</text>
    <text x="180" y="110" font-family="Arial" font-size="12" text-anchor="middle">token₃</text>
    <text x="90" y="150" font-family="Arial" font-size="12" text-anchor="middle">token₄</text>
    <text x="150" y="190" font-family="Arial" font-size="12" text-anchor="middle">token₅</text>
    
    <!-- Initial relationships -->
    <line x1="60" y1="80" x2="120" y2="100" stroke="#1565c0" stroke-width="1" stroke-opacity="0.5"/>
    <line x1="120" y1="100" x2="180" y2="120" stroke="#1565c0" stroke-width="1" stroke-opacity="0.5"/>
    <line x1="90" y1="160" x2="150" y2="200" stroke="#1565c0" stroke-width="1" stroke-opacity="0.5"/>
    <line x1="60" y1="80" x2="90" y2="160" stroke="#1565c0" stroke-width="1" stroke-opacity="0.5"/>
  </g>
  
  <!-- Middle: Attention calculation -->
  <g transform="translate(380, 100)">
    <rect width="140" height="300" rx="10" fill="#f0f4ff" stroke="#3b82f6" stroke-width="2"/>
    <text x="70" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Attention</text>
    
    <!-- Formula -->
    <text x="70" y="70" font-family="Arial" font-size="14" text-anchor="middle">A = softmax(</text>
    <text x="70" y="90" font-family="Arial" font-size="14" text-anchor="middle">QK^T/√d</text>
    <text x="70" y="110" font-family="Arial" font-size="14" text-anchor="middle">)V</text>
    
    <!-- Geometric interpretation -->
    <text x="70" y="150" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">Creates weighted</text>
    <text x="70" y="170" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">connections based</text>
    <text x="70" y="190" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">on relevance</text>
    
    <!-- Arrows indicating transformation -->
    <path d="M70,220 L70,250" stroke="#3b82f6" stroke-width="2" marker-end="url(#arrowhead)" fill="none"/>
  </g>
  
  <!-- Right side: Transformed space -->
  <g transform="translate(550, 100)">
    <rect width="250" height="300" rx="10" fill="#e3f2fd" stroke="#1565c0" stroke-width="2"/>
    <text x="125" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">After Attention</text>
    
    <!-- Transformed vector points -->
    <circle cx="70" cy="110" r="5" fill="#1565c0"/>
    <circle cx="130" cy="90" r="5" fill="#1565c0"/>
    <circle cx="170" cy="100" r="5" fill="#1565c0"/>
    <circle cx="110" cy="170" r="5" fill="#1565c0"/>
    <circle cx="160" cy="180" r="5" fill="#1565c0"/>
    
    <!-- Token labels -->
    <text x="70" y="100" font-family="Arial" font-size="12" text-anchor="middle">token₁</text>
    <text x="130" y="80" font-family="Arial" font-size="12" text-anchor="middle">token₂</text>
    <text x="170" y="90" font-family="Arial" font-size="12" text-anchor="middle">token₃</text>
    <text x="110" y="160" font-family="Arial" font-size="12" text-anchor="middle">token₄</text>
    <text x="160" y="170" font-family="Arial" font-size="12" text-anchor="middle">token₅</text>
    
    <!-- New stronger relationships -->
    <line x1="70" y1="110" x2="130" y2="90" stroke="#1565c0" stroke-width="2" stroke-opacity="0.7"/>
    <line x1="130" y1="90" x2="170" y2="100" stroke="#1565c0" stroke-width="1" stroke-opacity="0.3"/>
    <line x1="110" y1="170" x2="160" y2="180" stroke="#1565c0" stroke-width="2" stroke-opacity="0.7"/>
    <line x1="70" y1="110" x2="170" y2="100" stroke="#1565c0" stroke-width="2" stroke-opacity="0.7"/>
    <line x1="130" y1="90" x2="110" y2="170" stroke="#1565c0" stroke-width="1.5" stroke-opacity="0.5"/>
  </g>
  
  <!-- Caption explaining transformation -->
  <text x="450" y="430" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Attention as Geometric Transformation</text>
  <text x="450" y="460" font-family="Arial" font-size="14" text-anchor="middle">Tokens move in semantic space based on their relationships</text>
  
  <!-- Arrowhead Marker -->
  <defs>
    <marker id="arrowhead" markerWidth="10" markerHeight="7" refX="9" refY="3.5" orient="auto">
      <polygon points="0 0, 10 3.5, 0 7" fill="#3b82f6"/>
    </marker>
  </defs>
</svg>
```