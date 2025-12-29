
```xml
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 600">
  <!-- Background -->
  <rect width="900" height="600" fill="#f8f9fa"/>
  
  <!-- Title -->
  <text x="450" y="40" font-family="Arial" font-size="24" text-anchor="middle" font-weight="bold">Concept Manifolds in Semantic Space</text>
  
  <!-- 3D coordinate system -->
  <g transform="translate(450, 300)">
    <!-- Axes -->
    <line x1="0" y1="0" x2="200" y2="0" stroke="#333" stroke-width="2"/>
    <line x1="0" y1="0" x2="-100" y2="173.2" stroke="#333" stroke-width="2"/>
    <line x1="0" y1="0" x2="0" y2="-200" stroke="#333" stroke-width="2"/>
    
    <!-- Axis labels -->
    <text x="210" y="0" font-family="Arial" font-size="14" text-anchor="start">Dimension 1</text>
    <text x="-120" y="190" font-family="Arial" font-size="14" text-anchor="start">Dimension 2</text>
    <text x="0" y="-210" font-family="Arial" font-size="14" text-anchor="middle">Dimension 3</text>
    <text x="0" y="240" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">(Representing a 3D projection of a high-dimensional space)</text>
    
    <!-- "Animal" concept manifold (blue) -->
    <path d="M-50,-20 C0,-60 80,-50 100,-10 C120,30 80,90 20,80 C-40,70 -80,30 -50,-20 Z" fill="#dbeafe" stroke="#3b82f6" stroke-width="2" fill-opacity="0.5"/>
    <text x="20" y="20" font-family="Arial" font-size="16" text-anchor="middle">Animal</text>
    
    <!-- Specific animal points on the manifold -->
    <circle cx="-20" cy="-30" r="5" fill="#3b82f6"/>
    <text x="-20" y="-40" font-family="Arial" font-size="12" text-anchor="middle">dog</text>
    
    <circle cx="70" cy="0" r="5" fill="#3b82f6"/>
    <text x="70" y="-10" font-family="Arial" font-size="12" text-anchor="middle">cat</text>
    
    <circle cx="40" cy="60" r="5" fill="#3b82f6"/>
    <text x="40" y="50" font-family="Arial" font-size="12" text-anchor="middle">elephant</text>
    
    <circle cx="-30" cy="40" r="5" fill="#3b82f6"/>
    <text x="-30" y="30" font-family="Arial" font-size="12" text-anchor="middle">mouse</text>
    
    <!-- "Vehicle" concept manifold (green) -->
    <path d="M20,-100 C80,-120 140,-80 130,-30 C120,20 60,40 0,20 C-60,0 -40,-80 20,-100 Z" fill="#dcfce7" stroke="#16a34a" stroke-width="2" fill-opacity="0.5"/>
    <text x="60" y="-50" font-family="Arial" font-size="16" text-anchor="middle">Vehicle</text>
    
    <!-- Specific vehicle points -->
    <circle cx="20" cy="-90" r="5" fill="#16a34a"/>
    <text x="20" y="-100" font-family="Arial" font-size="12" text-anchor="middle">airplane</text>
    
    <circle cx="90" cy="-60" r="5" fill="#16a34a"/>
    <text x="90" y="-70" font-family="Arial" font-size="12" text-anchor="middle">car</text>
    
    <circle cx="60" cy="10" r="5" fill="#16a34a"/>
    <text x="60" y="0" font-family="Arial" font-size="12" text-anchor="middle">boat</text>
    
    <circle cx="-20" cy="-30" r="5" fill="#16a34a"/>
    <text x="-50" y="-30" font-family="Arial" font-size="12" text-anchor="end">bicycle</text>
    
    <!-- Manifold intersection -->
    <path d="M-30,-40 C-10,-50 0,-40 10,-30 C20,-20 10,0 -10,-10 C-30,-20 -50,-30 -30,-40 Z" fill="#818cf8" stroke="#4f46e5" stroke-width="2" fill-opacity="0.7"/>
    <text x="-10" y="-50" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">intersection</text>
    
    <!-- Geodesic path -->
    <path d="M-20,-30 C0,-10 20,0 40,60" stroke="#3b82f6" stroke-width="2" stroke-dasharray="5,5" fill="none"/>
    <text x="0" y="20" font-family="Arial" font-size="10" text-anchor="middle" font-style="italic">geodesic path</text>
  </g>
  
  <!-- Mathematical explanation -->
  <g transform="translate(450, 520)">
    <rect width="700" height="60" rx="10" fill="#f0f4ff" stroke="#3b82f6" stroke-width="2"/>
    <text x="0" y="25" font-family="Arial" font-size="14" text-anchor="start">• Concepts exist as manifolds (curved surfaces) in high-dimensional space</text>
    <text x="0" y="45" font-family="Arial" font-size="14" text-anchor="start">• Points on manifolds represent specific instances of concepts</text>
  </g>
</svg>
```
