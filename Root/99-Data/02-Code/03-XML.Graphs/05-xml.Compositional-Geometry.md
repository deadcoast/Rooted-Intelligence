
```xml
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 500">
  <!-- Background -->
  <rect width="900" height="500" fill="#f8f9fa"/>
  
  <!-- Title -->
  <text x="450" y="40" font-family="Arial" font-size="24" text-anchor="middle" font-weight="bold">Compositional Geometry in Vector Spaces</text>
  
  <!-- Vector Operations Section -->
  <g transform="translate(100, 120)">
    <rect width="200" height="150" rx="10" fill="#e6f1fe" stroke="#2563eb" stroke-width="2"/>
    <text x="100" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Vector Operations</text>
    
    <!-- Vector addition illustration -->
    <line x1="40" y1="100" x2="100" y2="60" stroke="#2563eb" stroke-width="2" marker-end="url(#arrowhead)"/>
    <line x1="100" y1="60" x2="160" y2="80" stroke="#2563eb" stroke-width="2" marker-end="url(#arrowhead)"/>
    <line x1="40" y1="100" x2="160" y2="80" stroke="#2563eb" stroke-width="2" stroke-dasharray="4,4"/>
    
    <text x="100" y="130" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">king - man + woman = queen</text>
  </g>
  
  <!-- Transformations Section -->
  <g transform="translate(350, 120)">
    <rect width="200" height="150" rx="10" fill="#e6f1fe" stroke="#2563eb" stroke-width="2"/>
    <text x="100" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Semantic Transformations</text>
    
    <!-- Transformation illustration -->
    <ellipse cx="60" cy="80" rx="30" ry="20" fill="none" stroke="#2563eb" stroke-width="2"/>
    <path d="M100,80 C120,80 120,80 140,80" stroke="#2563eb" stroke-width="2" marker-end="url(#arrowhead)"/>
    <ellipse cx="160" cy="80" rx="20" ry="30" fill="none" stroke="#2563eb" stroke-width="2"/>
    
    <text x="100" y="130" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">concept → modified concept</text>
  </g>
  
  <!-- Conceptual Blending Section -->
  <g transform="translate(600, 120)">
    <rect width="200" height="150" rx="10" fill="#e6f1fe" stroke="#2563eb" stroke-width="2"/>
    <text x="100" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Conceptual Blending</text>
    
    <!-- Blending illustration -->
    <circle cx="60" cy="70" r="25" fill="#2563eb" fill-opacity="0.3" stroke="#2563eb" stroke-width="1"/>
    <circle cx="140" cy="70" r="25" fill="#ec4899" fill-opacity="0.3" stroke="#ec4899" stroke-width="1"/>
    
    <path d="M100,100 C90,120 110,120 100,140" fill="#8b5cf6" fill-opacity="0.4" stroke="#8b5cf6" stroke-width="1"/>
    
    <text x="100" y="130" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">novel concept emergence</text>
  </g>
  
  <!-- Beyond Traditional Language section -->
  <g transform="translate(225, 300)">
    <rect width="450" height="150" rx="10" fill="#f0f4ff" stroke="#3b82f6" stroke-width="2"/>
    <text x="225" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Beyond Traditional Composition</text>
    
    <!-- Traditional vs Vector comparison -->
    <line x1="80" y1="60" x2="370" y2="60" stroke="#ddd" stroke-width="1"/>
    
    <text x="80" y="80" font-family="Arial" font-size="14" text-anchor="middle">Traditional Language</text>
    <text x="80" y="100" font-family="Arial" font-size="12" text-anchor="middle">Sequential</text>
    <text x="80" y="120" font-family="Arial" font-size="12" text-anchor="middle">Rule-based</text>
    <text x="80" y="140" font-family="Arial" font-size="12" text-anchor="middle">Limited combinations</text>
    
    <text x="370" y="80" font-family="Arial" font-size="14" text-anchor="middle">Vector Geometry</text>
    <text x="370" y="100" font-family="Arial" font-size="12" text-anchor="middle">Parallel</text>
    <text x="370" y="120" font-family="Arial" font-size="12" text-anchor="middle">Transformation-based</text>
    <text x="370" y="140" font-family="Arial" font-size="12" text-anchor="middle">Infinite combinations</text>
  </g>
  
  <!-- Arrowhead Marker -->
  <defs>
    <marker id="arrowhead" markerWidth="10" markerHeight="7" refX="9" refY="3.5" orient="auto">
      <polygon points="0 0, 10 3.5, 0 7" fill="#2563eb"/>
    </marker>
  </defs>
</svg>
```
