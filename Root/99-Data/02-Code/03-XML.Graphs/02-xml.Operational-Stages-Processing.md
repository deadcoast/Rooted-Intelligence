
```xml
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 500">
  <!-- Background -->
  <rect width="900" height="500" fill="#f9f9f9"/>
  
  <!-- Title -->
  <text x="450" y="40" font-family="Arial" font-size="24" text-anchor="middle" font-weight="bold">Operational Stages of LLM Processing</text>
  
  <!-- Stage boxes -->
  <g id="stage1">
    <rect x="50" y="100" width="160" height="300" rx="10" fill="#E3F2FD" stroke="#1565C0" stroke-width="2"/>
    <text x="130" y="130" font-family="Arial" font-size="18" text-anchor="middle" font-weight="bold">1. Tokenization</text>
    <line x1="70" y1="150" x2="190" y2="150" stroke="#1565C0" stroke-width="1"/>
    
    <text x="130" y="180" font-family="Arial" font-size="14" text-anchor="middle">Input → Token IDs</text>
    <text x="130" y="210" font-family="Arial" font-size="12" text-anchor="middle">Subword Units</text>
    <text x="130" y="230" font-family="Arial" font-size="12" text-anchor="middle">Position Encoding</text>
    
    <rect x="80" y="260" width="100" height="60" rx="5" fill="#BBDEFB" stroke="#1565C0" stroke-width="1"/>
    <text x="130" y="280" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">Statistical</text>
    <text x="130" y="300" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">Compression</text>
    <text x="130" y="320" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">of Language</text>
  </g>
  
  <g id="stage2">
    <rect x="250" y="100" width="160" height="300" rx="10" fill="#E8F5E9" stroke="#2E7D32" stroke-width="2"/>
    <text x="330" y="130" font-family="Arial" font-size="18" text-anchor="middle" font-weight="bold">2. Embedding</text>
    <line x1="270" y1="150" x2="390" y2="150" stroke="#2E7D32" stroke-width="1"/>
    
    <text x="330" y="180" font-family="Arial" font-size="14" text-anchor="middle">Tokens → Vectors</text>
    <text x="330" y="210" font-family="Arial" font-size="12" text-anchor="middle">High-Dimensional</text>
    <text x="330" y="230" font-family="Arial" font-size="12" text-anchor="middle">Semantic Space</text>
    
    <rect x="280" y="260" width="100" height="60" rx="5" fill="#C8E6C9" stroke="#2E7D32" stroke-width="1"/>
    <text x="330" y="280" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">Geometric</text>
    <text x="330" y="300" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">Representation</text>
    <text x="330" y="320" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">of Meaning</text>
  </g>
  
  <g id="stage3">
    <rect x="450" y="100" width="160" height="300" rx="10" fill="#FFF3E0" stroke="#E65100" stroke-width="2"/>
    <text x="530" y="130" font-family="Arial" font-size="18" text-anchor="middle" font-weight="bold">3. Attention</text>
    <line x1="470" y1="150" x2="590" y2="150" stroke="#E65100" stroke-width="1"/>
    
    <text x="530" y="180" font-family="Arial" font-size="14" text-anchor="middle">Context Integration</text>
    <text x="530" y="210" font-family="Arial" font-size="12" text-anchor="middle">Relational Weighting</text>
    <text x="530" y="230" font-family="Arial" font-size="12" text-anchor="middle">Multi-Head Processing</text>
    
    <rect x="480" y="260" width="100" height="60" rx="5" fill="#FFE0B2" stroke="#E65100" stroke-width="1"/>
    <text x="530" y="280" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">Parallel</text>
    <text x="530" y="300" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">Contextual</text>
    <text x="530" y="320" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">Reasoning</text>
  </g>
  
  <g id="stage4">
    <rect x="650" y="100" width="160" height="300" rx="10" fill="#F3E5F5" stroke="#6A1B9A" stroke-width="2"/>
    <text x="730" y="130" font-family="Arial" font-size="18" text-anchor="middle" font-weight="bold">4. Projection</text>
    <line x1="670" y1="150" x2="790" y2="150" stroke="#6A1B9A" stroke-width="1"/>
    
    <text x="730" y="180" font-family="Arial" font-size="14" text-anchor="middle">Vectors → Tokens</text>
    <text x="730" y="210" font-family="Arial" font-size="12" text-anchor="middle">Probability Distribution</text>
    <text x="730" y="230" font-family="Arial" font-size="12" text-anchor="middle">Dimensional Reduction</text>
    
    <rect x="680" y="260" width="100" height="60" rx="5" fill="#E1BEE7" stroke="#6A1B9A" stroke-width="1"/>
    <text x="730" y="280" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">Human-</text>
    <text x="730" y="300" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">Interpretable</text>
    <text x="730" y="320" font-family="Arial" font-size="12" text-anchor="middle" font-style="italic">Translation</text>
  </g>
  
  <!-- Connection arrows -->
  <path d="M210,250 L250,250" stroke="#333" stroke-width="2" marker-end="url(#arrowhead)"/>
  <path d="M410,250 L450,250" stroke="#333" stroke-width="2" marker-end="url(#arrowhead)"/>
  <path d="M610,250 L650,250" stroke="#333" stroke-width="2" marker-end="url(#arrowhead)"/>
  
  <!-- Transformation labels -->
  <text x="230" y="230" font-family="Arial" font-size="12" text-anchor="middle">Discretization</text>
  <text x="430" y="230" font-family="Arial" font-size="12" text-anchor="middle">Contextualization</text>
  <text x="630" y="230" font-family="Arial" font-size="12" text-anchor="middle">Generation</text>
  
  <!-- Reality layer label -->
  <rect x="50" y="420" width="760" height="40" rx="5" fill="#ECEFF1" stroke="#455A64" stroke-width="2"/>
  <text x="430" y="445" font-family="Arial" font-size="18" text-anchor="middle" font-weight="bold">Underlying Reality: Continuous Vector Space Operations</text>
  
  <!-- Arrowhead Marker -->
  <defs>
    <marker id="arrowhead" markerWidth="10" markerHeight="7" refX="9" refY="3.5" orient="auto">
      <polygon points="0 0, 10 3.5, 0 7" fill="#333"/>
    </marker>
  </defs>
</svg>
```