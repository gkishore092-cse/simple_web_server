# EX01 Developing a Simple Webserver

# Date:19/09/2025
# AIM:
To develop a simple webserver to serve html pages and display the configuration details of laptop.

# DESIGN STEPS:
## Step 1:
HTML content creation.

## Step 2:
Design of webserver workflow.

## Step 3:
Implementation using Python code.

## Step 4:
Serving the HTML pages.

## Step 5:
Testing the webserver.

# PROGRAM:
```
from http.server import HTTPServer, BaseHTTPRequestHandler
content =
<!DOCTYPE html>
<html>
<head>
    <title>Simple Web Server</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background: #f0f0f0;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            max-width: 600px;
            margin: 0 auto;
        }
        h1 {
            color: #333;
            text-align: center;
        }
        .specs {
            line-height: 1.6;
        }
        .spec-name {
            display: inline-block;
            width: 120px;
            font-weight: bold;
            vertical-align: top;
        }
        .spec-value {
            display: inline-block;
            vertical-align: top;
        }
        .footer {
            margin-top: 20px;
            text-align: center;
            font-size: 14px;
            color: #666;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>MY LAPTOP SPECIFICATIONS</h1>
        <div class="specs">
            <p><span class="spec-name">MODEL:</span> <span class="spec-value">HP Victus 15</span></p>
            <p><span class="spec-name">PROCESSOR:</span> <span class="spec-value">Intel Core i5-13420H (13th Gen)</span></p>
            <p><span class="spec-name">GRAPHICS:</span> <span class="spec-value">NVIDIA® GeForce RTX™ 3050</span></p>
            <p><span class="spec-name">DISPLAY:</span> <span class="spec-value">15.6-inch (39.6 cm) Full HD (1920 x 1080) IPS display with a 144 Hz refresh rate, anti-glare, and micro-edge bezels.</span></p>
            <p><span class="spec-name">RAM:</span> <span class="spec-value">16GB DDR4 (expandable to 32GB)</span></p>
            <p><span class="spec-name">STORAGE:</span> <span class="spec-value">512 GB PCIe® Gen4 NVMe™ M.2 SSD.</span></p>
            <p><span class="spec-name">KEYBOARD:</span> <span class="spec-value">YES</span></p>
            <p><span class="spec-name">COOLING:</span> <span class="spec-value">Self-cleaning cooling system</span></p>
            <p><span class="spec-name">BATTERY:</span> <span class="spec-value">70Wh, up to 8 hours of mixed usage</span></p>
            <p><span class="spec-name">OS:</span> <span class="spec-value">Windows 11 Pro</span></p>
            <p><span class="spec-name">CONNECTIVITY:</span> <span class="spec-value">Wi-Fi 6, Bluetooth 5.2</span></p>
            <p><span class="spec-name">DURABILITY:</span> <span class="spec-value">plastic build</span></p>
            <p><span class="spec-name">WEIGHT:</span> <span class="spec-value">2.3 kg</span></p>
        </div>
        <div class="footer">
            <p>Register Number: YOUR_REG_NO | Name: YOUR_NAME</p>
        </div>
    </div>
</body>
</html>
```
# OUTPUT:
![alt text](<Screenshot 2025-09-15 201047.png>)
g
![alt text](<Screenshot 2025-09-19 190400.png>)
# RESULT:
The program for implementing simple webserver is executed successfully.
