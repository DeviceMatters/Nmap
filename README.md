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
  <p><strong>Nmap Network Scan of 192.168.139.129/24</strong></p>

  <h2>📝 Description</h2>
  <p>
    This project involves scanning a loca host/network using <strong>Nmap (Network Mapper)</strong> to identify open ports,
    services, and potential vulnerabilities. The objective is to gain insight into the network's exposure and assess
    security configurations.
  </p>

  <h2>🛠️ Tools Used</h2>
  <ul>
    <li><strong>Nmap</strong>: Network scanning tool</li>
  </ul>

  <h2>🧪 Scan Commands Used</h2>
  nmap -sS -A 192.168.139.129/24

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
        <td>7070/tcp</td>
        <td>open</td>
        <td>RSTP</td>
      </tr>
      <tr>
        <td>53/tcp</td>
        <td>open</td>
        <td>DNS</td>
        <td>dnsmasq 2.51</td>
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
    <li>Open ports: 53,7070</li>
    <li>Services running: DNS , RSTP</li>
    <li>Potential vulnerabilities: port - 53  DNS hijacking, DNS spoofing, DDoS attacks, DNS Tunneling, Domain Shadowing.
</li>
    <li>Potential vulnerabilities: port - 7070 unauthorized access and malware distribution
</li>
  </ul>
  <h2>📅 Date of Scan</h2>
  <p>26/05/2025</p>

</body>
</html>
