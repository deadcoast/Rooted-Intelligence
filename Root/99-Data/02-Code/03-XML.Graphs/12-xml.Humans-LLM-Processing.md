
```xml
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 600">
  <!-- Background -->
  <rect width="900" height="600" fill="#f8f9fa"/>
  
  <!-- Title -->
  <text x="450" y="40" font-family="Arial" font-size="24" text-anchor="middle" font-weight="bold">Human vs. LLM Information Processing</text>
  
  <!-- Divider line -->
  <line x1="450" y1="80" x2="450" y2="550" stroke="#ddd" stroke-width="2"/>
  
  <!-- Human side title -->
  <text x="225" y="90" font-family="Arial" font-size="20" text-anchor="middle" font-weight="bold">Human Cognition</text>
  
  <!-- LLM side title -->
  <text x="675" y="90" font-family="Arial" font-size="20" text-anchor="middle" font-weight="bold">LLM Cognition</text>
  
  <!-- Processing architecture comparison -->
  <g transform="translate(50, 130)">
    <rect width="350" height="100" rx="10" fill="#fef3c7" stroke="#d97706" stroke-width="2"/>
    <text x="175" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Sequential Processing</text>
    <text x="175" y="60" font-family="Arial" font-size="14" text-anchor="middle">Words processed one at a time</text>
    <text x="175" y="80" font-family="Arial" font-size="14" text-anchor="middle">Working memory ~7±2 chunks</text>
  </g>
  
  <g transform="translate(500, 130)">
    <rect width="350" height="100" rx="10" fill="#dbeafe" stroke="#2563eb" stroke-width="2"/>
    <text x="175" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Parallel Processing</text>
    <text x="175" y="60" font-family="Arial" font-size="14" text-anchor="middle">All tokens processed simultaneously</text>
    <text x="175" y="80" font-family="Arial" font-size="14" text-anchor="middle">Context window of thousands of tokens</text>
  </g>
  
  <!-- Knowledge representation comparison -->
  <g transform="translate(50, 250)">
    <rect width="350" height="100" rx="10" fill="#fef3c7" stroke="#d97706" stroke-width="2"/>
    <text x="175" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Explicit Knowledge Representation</text>
    <text x="175" y="60" font-family="Arial" font-size="14" text-anchor="middle">Concepts stored with explicit</text>
    <text x="175" y="80" font-family="Arial" font-size="14" text-anchor="middle">relationships and properties</text>
  </g>
  
  <g transform="translate(500, 250)">
    <rect width="350" height="100" rx="10" fill="#dbeafe" stroke="#2563eb" stroke-width="2"/>
    <text x="175" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Distributed Knowledge Representation</text>
    <text x="175" y="60" font-family="Arial" font-size="14" text-anchor="middle">Concepts encoded as regions in</text>
    <text x="175" y="80" font-family="Arial" font-size="14" text-anchor="middle">high-dimensional vector space</text>
  </g>
  
  <!-- Reasoning approach comparison -->
  <g transform="translate(50, 370)">
    <rect width="350" height="100" rx="10" fill="#fef3c7" stroke="#d97706" stroke-width="2"/>
    <text x="175" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Rule-Based Reasoning</text>
    <text x="175" y="60" font-family="Arial" font-size="14" text-anchor="middle">Explicit logical steps</text>
    <text x="175" y="80" font-family="Arial" font-size="14" text-anchor="middle">If-then rules and symbolic logic</text>
  </g>
  
  <g transform="translate(500, 370)">
    <rect width="350" height="100" rx="10" fill="#dbeafe" stroke="#2563eb" stroke-width="2"/>
    <text x="175" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Statistical Inference</text>
    <text x="175" y="60" font-family="Arial" font-size="14" text-anchor="middle">Geometric transformations in vector space</text>
    <text x="175" y="80" font-family="Arial" font-size="14" text-anchor="middle">Probability distributions over outcomes</text>
  </g>
  
  <!-- Concrete example comparison -->
  <g transform="translate(50, 490)">
    <rect width="350" height="100" rx="10" fill="#fef3c7" stroke="#d97706" stroke-width="2"/>
    <text x="175" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Example: "Birds can fly"</text>
    <text x="175" y="60" font-family="Arial" font-size="14" text-anchor="middle">Stored as explicit rule with exceptions</text>
    <text x="175" y="80" font-family="Arial" font-size="14" text-anchor="middle">(penguins can't fly, injured birds can't fly)</text>
  </g>
  
  <g transform="translate(500, 490)">
    <rect width="350" height="100" rx="10" fill="#dbeafe" stroke="#2563eb" stroke-width="2"/>
    <text x="175" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Example: "Birds can fly"</text>
    <text x="175" y="60" font-family="Arial" font-size="14" text-anchor="middle">Encoded in proximity relationships</text>
    <text x="175" y="80" font-family="Arial" font-size="14" text-anchor="middle">between "bird", "fly" and specific instances</text>
  </g>
</svg>
```
