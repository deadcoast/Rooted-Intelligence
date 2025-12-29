
```xml
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 600">
  <!-- Background -->
  <rect width="900" height="600" fill="#f8f9fa"/>
  
  <!-- Title -->
  <text x="450" y="40" font-family="Arial" font-size="24" text-anchor="middle" font-weight="bold">Reasoning Task Comparison: Human vs. LLM</text>
  
  <!-- Task: Logical Inference -->
  <text x="450" y="80" font-family="Arial" font-size="20" text-anchor="middle">Task: "All birds have feathers. A penguin is a bird. Does a penguin have feathers?"</text>
  
  <!-- Human reasoning process -->
  <g transform="translate(50, 120)">
    <rect width="350" height="210" rx="10" fill="#fef3c7" stroke="#d97706" stroke-width="2"/>
    <text x="175" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Human Syllogistic Reasoning</text>
    
    <!-- Step 1 -->
    <rect x="30" y="50" width="290" height="30" rx="5" fill="#fef9c3" stroke="#ca8a04" stroke-width="1"/>
    <text x="175" y="70" font-family="Arial" font-size="14" text-anchor="middle">1. Recall rule: "All birds have feathers"</text>
    
    <!-- Step 2 -->
    <rect x="30" y="90" width="290" height="30" rx="5" fill="#fef9c3" stroke="#ca8a04" stroke-width="1"/>
    <text x="175" y="110" font-family="Arial" font-size="14" text-anchor="middle">2. Classify: "A penguin is a bird"</text>
    
    <!-- Step 3 -->
    <rect x="30" y="130" width="290" height="30" rx="5" fill="#fef9c3" stroke="#ca8a04" stroke-width="1"/>
    <text x="175" y="150" font-family="Arial" font-size="14" text-anchor="middle">3. Apply rule: "Birds have feathers"</text>
    
    <!-- Conclusion -->
    <rect x="30" y="170" width="290" height="30" rx="5" fill="#fef9c3" stroke="#ca8a04" stroke-width="1"/>
    <text x="175" y="190" font-family="Arial" font-size="14" text-anchor="middle">4. Conclude: "Yes, penguins have feathers"</text>
  </g>
  
  <!-- LLM reasoning process -->
  <g transform="translate(500, 120)">
    <rect width="350" height="210" rx="10" fill="#dbeafe" stroke="#2563eb" stroke-width="2"/>
    <text x="175" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">LLM Vector Space Operations</text>
    
    <!-- Step 1 -->
    <rect x="30" y="50" width="290" height="30" rx="5" fill="#e0f2fe" stroke="#0284c7" stroke-width="1"/>
    <text x="175" y="70" font-family="Arial" font-size="14" text-anchor="middle">1. Encode input as vector representation</text>
    
    <!-- Step 2 -->
    <rect x="30" y="90" width="290" height="30" rx="5" fill="#e0f2fe" stroke="#0284c7" stroke-width="1"/>
    <text x="175" y="110" font-family="Arial" font-size="14" text-anchor="middle">2. Activate regions: "bird", "penguin", "feathers"</text>
    
    <!-- Step 3 -->
    <rect x="30" y="130" width="290" height="30" rx="5" fill="#e0f2fe" stroke="#0284c7" stroke-width="1"/>
    <text x="175" y="150" font-family="Arial" font-size="14" text-anchor="middle">3. Measure vector relationships</text>
    
    <!-- Conclusion -->
    <rect x="30" y="170" width="290" height="30" rx="5" fill="#e0f2fe" stroke="#0284c7" stroke-width="1"/>
    <text x="175" y="190" font-family="Arial" font-size="14" text-anchor="middle">4. High p(feathers|penguin) → "Yes"</text>
  </g>
  
  <!-- Task: Analogy -->
  <text x="450" y="380" font-family="Arial" font-size="20" text-anchor="middle">Task: "King is to Queen as Man is to ____?"</text>
  
  <!-- Human analogy process -->
  <g transform="translate(50, 420)">
    <rect width="350" height="150" rx="10" fill="#fef3c7" stroke="#d97706" stroke-width="2"/>
    <text x="175" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">Human Analogy Processing</text>
    
    <!-- Step 1 -->
    <rect x="30" y="50" width="290" height="30" rx="5" fill="#fef9c3" stroke="#ca8a04" stroke-width="1"/>
    <text x="175" y="70" font-family="Arial" font-size="14" text-anchor="middle">1. Identify relationship: "female version of"</text>
    
    <!-- Step 2 -->
    <rect x="30" y="90" width="290" height="30" rx="5" fill="#fef9c3" stroke="#ca8a04" stroke-width="1"/>
    <text x="175" y="110" font-family="Arial" font-size="14" text-anchor="middle">2. Apply relationship to "Man"</text>
    
    <!-- Conclusion -->
    <rect x="30" y="130" width="290" height="30" rx="5" fill="#fef9c3" stroke="#ca8a04" stroke-width="1"/>
    <text x="175" y="150" font-family="Arial" font-size="14" text-anchor="middle">3. Conclude: "Woman"</text>
  </g>
  
  <!-- LLM analogy process -->
  <g transform="translate(500, 420)">
    <rect width="350" height="150" rx="10" fill="#dbeafe" stroke="#2563eb" stroke-width="2"/>
    <text x="175" y="30" font-family="Arial" font-size="16" text-anchor="middle" font-weight="bold">LLM Vector Arithmetic</text>
    
    <!-- Step 1 -->
    <rect x="30" y="50" width="290" height="30" rx="5" fill="#e0f2fe" stroke="#0284c7" stroke-width="1"/>
    <text x="175" y="70" font-family="Arial" font-size="14" text-anchor="middle">1. Calculate: v̅queen - v̅king + v̅man</text>
    
    <!-- Step 2 -->
    <rect x="30" y="90" width="290" height="30" rx="5" fill="#e0f2fe" stroke="#0284c7" stroke-width="1"/>
    <text x="175" y="110" font-family="Arial" font-size="14" text-anchor="middle">2. Find nearest token to result vector</text>
    
    <!-- Conclusion -->
    <rect x="30" y="130" width="290" height="30" rx="5" fill="#e0f2fe" stroke="#0284c7" stroke-width="1"/>
    <text x="175" y="150" font-family="Arial" font-size="14" text-anchor="middle">3. Result vector ≈ v̅woman</text>
  </g>
</svg>
```