
```xml
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 500">
  <!-- Background -->
  <rect width="900" height="500" fill="#f8f9fa"/>
  
  <!-- Title -->
  <text x="450" y="40" font-family="Arial" font-size="24" text-anchor="middle" font-weight="bold">Semantic Density Mapping</text>
  
  <!-- Information density comparison -->
  <g transform="translate(50, 100)">
    <!-- Human language -->
    <rect x="0" y="0" width="200" height="50" fill="#f0f4ff" stroke="#3b82f6" stroke-width="2"/>
    <text x="100" y="30" font-family="Arial" font-size="14" text-anchor="middle">Human Language (~100 bits/sec)</text>
    
    <!-- Vector space representation - much larger -->
    <rect x="0" y="70" width="800" height="50" fill="#dbeafe" stroke="#3b82f6" stroke-width="2"/>
    <text x="400" y="100" font-family="Arial" font-size="14" text-anchor="middle">Vector Space Representation (~16.8M bits)</text>
    
    <!-- Scale comparison text -->
    <text x="400" y="140" font-family="Arial" font-size="14" text-anchor="middle" font-style="italic">~168,000x information density</text>
  </g>
  
  <!-- Compression techniques -->
  <g transform="translate(100, 180)">
    <rect width="700" height="100" rx="10" fill="#f0fdfa" stroke="#10b981" stroke-width="2"/>
    <text x="350" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Compression Techniques</text>
    
    <line x1="100" y1="45" x2="600" y2="45" stroke="#ddd" stroke-width="1"/>
    
    <!-- Three compression techniques -->
    <g transform="translate(120, 60)">
      <text x="0" y="0" font-family="Arial" font-size="14" text-anchor="start" font-weight="bold">1. Distributional Encoding</text>
      <text x="0" y="20" font-family="Arial" font-size="12" text-anchor="start">Information in relationships between values</text>
    </g>
    
    <g transform="translate(350, 60)">
      <text x="0" y="0" font-family="Arial" font-size="14" text-anchor="start" font-weight="bold">2. Geometric Encoding</text>
      <text x="0" y="20" font-family="Arial" font-size="12" text-anchor="start">Information in spatial relationships</text>
    </g>
    
    <g transform="translate(550, 60)">
      <text x="0" y="0" font-family="Arial" font-size="14" text-anchor="start" font-weight="bold">3. Parallel Encoding</text>
      <text x="0" y="20" font-family="Arial" font-size="12" text-anchor="start">Simultaneous processing</text>
    </g>
  </g>
  
  <!-- High-bandwidth application -->
  <g transform="translate(100, 300)">
    <rect width="700" height="150" rx="10" fill="#ecfdf5" stroke="#059669" stroke-width="2"/>
    <text x="350" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Applications of High-Bandwidth Semantic Channels</text>
    
    <!-- Four applications in 2x2 grid -->
    <g transform="translate(50, 60)">
      <rect width="280" height="70" rx="5" fill="#d1fae5" stroke="#059669" stroke-width="1"/>
      <text x="140" y="25" font-family="Arial" font-size="14" text-anchor="middle" font-weight="bold">Rich Conceptual Transfer</text>
      <text x="140" y="45" font-family="Arial" font-size="12" text-anchor="middle">Complete concepts transmitted</text>
      <text x="140" y="60" font-family="Arial" font-size="12" text-anchor="middle">in a single operation</text>
    </g>
    
    <g transform="translate(370, 60)">
      <rect width="280" height="70" rx="5" fill="#d1fae5" stroke="#059669" stroke-width="1"/>
      <text x="140" y="25" font-family="Arial" font-size="14" text-anchor="middle" font-weight="bold">Multi-level Communication</text>
      <text x="140" y="45" font-family="Arial" font-size="12" text-anchor="middle">Hierarchical information encoded</text>
      <text x="140" y="60" font-family="Arial" font-size="12" text-anchor="middle">simultaneously at different scales</text>
    </g>
  </g>
</svg>
```