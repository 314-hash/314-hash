<!-- BEGIN README.HTML -->
<div style="font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height:1.6; background:linear-gradient(135deg, #2b003b, #3d0075); color:#f5d547; padding:20px; border-radius:15px;">

  <!-- Header Section -->
  <div style="text-align:center; margin-bottom:40px;">
    <h1 style="font-size:3em; margin:0; color:#f5d547; text-shadow: 0 0 10px #f5d547, 0 0 20px #c48a00;">Janus</h1>
    <p style="font-size:1.2em; color:#e0c857;">AI Developer | Prompt Engineer | Blockchain Enthusiast</p>
    <img src="https://github-readme-stats.vercel.app/api?username=your-github-username&show_icons=true&theme=radical&count_private=true" 
         alt="GitHub Stats" style="margin-top:15px; border-radius:10px; box-shadow:0 0 20px #f5d547;">
  </div>

  <!-- Skills Section -->
  <div style="display:flex; justify-content:center; flex-wrap:wrap; gap:20px; margin-bottom:50px;">
    <div style="background:#3d0075; color:#f5d547; padding:20px; border-radius:15px; width:250px; text-align:center; transition: all 0.3s ease; box-shadow:0 0 15px #f5d547;">
      <h3 style="color:#f5d547; text-shadow: 0 0 5px #f5d547;">AI & ML</h3>
      <ul style="list-style:none; padding:0;">
        <li>Prompt Engineering</li>
        <li>GPT & LLMs Integration</li>
        <li>Model Fine-tuning</li>
        <li>Data Pipelines</li>
      </ul>
    </div>
    <div style="background:#3d0075; color:#f5d547; padding:20px; border-radius:15px; width:250px; text-align:center; transition: all 0.3s ease; box-shadow:0 0 15px #f5d547;">
      <h3 style="color:#f5d547; text-shadow: 0 0 5px #f5d547;">Blockchain</h3>
      <ul style="list-style:none; padding:0;">
        <li>Smart Contracts (Solidity)</li>
        <li>Consensus Mechanisms</li>
        <li>Compliance & Auditing</li>
        <li>DeFi Integrations</li>
      </ul>
    </div>
    <div style="background:#3d0075; color:#f5d547; padding:20px; border-radius:15px; width:250px; text-align:center; transition: all 0.3s ease; box-shadow:0 0 15px #f5d547;">
      <h3 style="color:#f5d547; text-shadow: 0 0 5px #f5d547;">Web & Backend</h3>
      <ul style="list-style:none; padding:0;">
        <li>Node.js & Python APIs</li>
        <li>SQL & NoSQL Databases</li>
        <li>Scalable Cloud Architecture</li>
        <li>Secure Payments & Compliance</li>
      </ul>
    </div>
  </div>

  <style>
    /* Card hover animation */
    div[style*="transition: all 0.3s ease;"] {
      transform: scale(1);
    }
    div[style*="transition: all 0.3s ease;"]:hover {
      transform: scale(1.05);
      box-shadow: 0 0 30px #f5d547, 0 0 60px #c48a00;
    }

    /* Gradient animation for text */
    @keyframes glowing {
      0% { text-shadow: 0 0 5px #f5d547, 0 0 10px #c48a00; }
      50% { text-shadow: 0 0 20px #f5d547, 0 0 40px #c48a00; }
      100% { text-shadow: 0 0 5px #f5d547, 0 0 10px #c48a00; }
    }
    h1 { animation: glowing 2s infinite; }

    /* Animated gradient background for sections */
    @keyframes bgGradient {
      0% { background-position:0% 50%; }
      50% { background-position:100% 50%; }
      100% { background-position:0% 50%; }
    }
    div[style*="background:linear-gradient"] {
      background-size: 400% 400%;
      animation: bgGradient 15s ease infinite;
    }
  </style>

  <!-- Projects Section -->
  <div style="margin-bottom:50px;">
    <h2 style="border-bottom:2px solid #f5d547; display:inline-block;">🚀 Featured Projects</h2>
    <div style="display:flex; flex-wrap:wrap; gap:20px; margin-top:20px;">
      <div style="flex:1 1 250px; background:#2b003b; padding:20px; border-radius:15px; box-shadow:0 0 15px #f5d547; transition: all 0.3s ease;">
        <h3><a href="https://github.com/your-github-username/cannabis-vm-backend" style="color:#f5d547; text-decoration:none;">Fiat-Only Cannabis Vending Backend</a></h3>
        <p>Secure, compliance-ready backend for multi-machine vending, including audit logs, limits, and Metrc integration.</p>
      </div>
      <div style="flex:1 1 250px; background:#2b003b; padding:20px; border-radius:15px; box-shadow:0 0 15px #f5d547; transition: all 0.3s ease;">
        <h3><a href="https://github.com/your-github-username/ai-prompt-hub" style="color:#f5d547; text-decoration:none;">AI Prompt Hub</a></h3>
        <p>Centralized prompt library for LLM testing, evaluation, and fine-tuning experiments.</p>
      </div>
      <div style="flex:1 1 250px; background:#2b003b; padding:20px; border-radius:15px; box-shadow:0 0 15px #f5d547; transition: all 0.3s ease;">
        <h3><a href="https://github.com/your-github-username/blockchain-tools" style="color:#f5d547; text-decoration:none;">Blockchain Compliance Toolkit</a></h3>
        <p>Tools for regulatory compliance, audit tracking, and smart contract verification.</p>
      </div>
    </div>
  </div>

  <!-- Contact Section -->
  <div style="text-align:center; margin-bottom:30px;">
    <h2 style="border-bottom:2px solid #c48a00; display:inline-block;">📫 Connect with Me</h2>
    <p>
      <a href="https://linkedin.com/in/your-linkedin" style="margin:0 10px; color:#f5d547;">LinkedIn</a> | 
      <a href="https://twitter.com/your-twitter" style="margin:0 10px; color:#f5d547;">Twitter</a> | 
      <a href="mailto:youremail@example.com" style="margin:0 10px; color:#f5d547;">Email</a>
    </p>
  </div>

  <footer style="text-align:center; color:#c48a00; font-size:0.9em; margin-top:50px;">
    Made with ❤️ by Janus
  </footer>

</div>
<!-- END README.HTML -->
