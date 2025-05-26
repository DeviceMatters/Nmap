# Nmap
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Nmap Scan Report</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background-color: #f9f9f9;
      padding: 20px;
    }
    h1, h2 {
      color: #2c3e50;
    }
    code, pre {
      background-color: #eee;
      padding: 8px;
      display: block;
      border-left: 4px solid #007acc;
      margin: 10px 0;
      white-space: pre-wrap;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin: 10px 0;
    }
    th, td {
      border: 1px solid #ccc;
      padding: 8px;
      text-align: left;
    }
    th {
      background-color: #007acc;
      color: white;
    }
  </style>
</head>
<body>

  <h1>📌 Project Title</h1>
  <p><strong>Nmap Network Scan of [Target IP/Domain]</strong></p>

  <h2>📝 Description</h2>
  <p>
    This project involves scanning a host/network using <strong>Nmap (Network Mapper)</strong> to identify open ports,
    services, and potential vulnerabilities. The objective is to gain insight into the network's exposure and assess
    security configurations.
  </p>

  <h2>🛠️ Tools Used</h2>
  <ul>
    <li><strong>Nmap</strong>: Network scanning tool</li>
    <li><em>[Optional]</em> OS: Linux / Windows / macOS</li>
    <li><em>[Optional]</em> Other Tools: e.g., grep, Wireshark, Zenmap</li>
  </ul>

  <h2>🧪 Scan Commands Used</h2>
  <pre><code># Basic port scan
nmap &lt;target&gt;

# Service version detection
nmap -sV &lt;target&gt;

# OS detection
nmap -O &lt;target&gt;

# Aggressive scan (use with caution)
nmap -A &lt;target&gt;

# Scan specific ports
nmap -p 22,80,443 &lt;target&gt;
</code></pre>

  <h2>📊 Scan Results Summary</h2>
  <table>
    <thead>
      <tr>
        <th>Port</th>
        <th>State</th>
        <th>Service</th>
        <th>Version (if detected)</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>22</td>
        <td>open</td>
        <td>ssh</td>
        <td>OpenSSH 7.6p1 Ubuntu</td>
      </tr>
      <tr>
        <td>80</td>
        <td>open</td>
        <td>http</td>
        <td>Apache httpd 2.4.29</td>
      </tr>
      <tr>
        <td>...</td>
        <td>...</td>
        <td>...</td>
        <td>...</td>
      </tr>
    </tbody>
  </table>

  <h2>🔐 Observations</h2>
  <ul>
    <li>Open ports: [List open ports]</li>
    <li>Services running: [List services]</li>
    <li>Potential vulnerabilities: [If applicable]</li>
    <li>Operating system detected: [OS Name / Version]</li>
  </ul>

  <h2>⚠️ Notes</h2>
  <p>
    Ensure permission before scanning any third-party or external networks. <br>
    Scanning without consent may be <strong>illegal</strong> and against ethical guidelines.
  </p>

  <h2>📁 Output Files</h2>
  <ul>
    <li><code>scan_results.txt</code> – Raw Nmap output</li>
    <li><code>scan_summary.md</code> – Parsed summary (optional)</li>
    <li><code>screenshots/</code> – Any screenshots or visual reports (if applicable)</li>
  </ul>

  <h2>📚 References</h2>
  <ul>
    <li><a href="https://nmap.org/book/man.html" target="_blank">Nmap Documentation</a></li>
    <li><a href="https://nmap.org/book/man-briefoptions.html" target="_blank">Common Nmap Commands</a></li>
  </ul>

  <h2>📅 Date of Scan</h2>
  <p>YYYY-MM-DD</p>

</body>
</html>
