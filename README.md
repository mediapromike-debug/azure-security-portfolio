# Azure Security Projects – April 2026

## Project 1: Secure Azure IoT + AI Platform for Chemical Hazard Detection Sensor System
Built specifically for an AI chemical sensor startup (IoT devices collecting real-time chemical data → secure cloud ingestion → protected AI analysis).
# Azure Security Projects – April 2026

## Project 1: Secure Azure IoT + AI Platform for Chemical Hazard Detection Sensor System

**Project Overview**  
I built this secure Azure backend specifically thinking about an AI-powered chemical hazard detection sensor system (real-time dangerous chemical detection for homes and commercial buildings).  

The architecture focuses on:
- Secure ingestion of sensor data from IoT devices
- Protected storage of sensitive chemical readings
- Proper network isolation and least-privilege principles
- Secure management of secrets and keys

### Resources Created

- **IoT Hub**: `iothub-chemical-sensor-demo`  
  → Central hub for receiving real-time data from chemical sensors

- **Key Vault**: `kv-chemical-sensor-demo`  
  → Secure storage for encryption keys, connection strings, and secrets

- **Virtual Network**: `vnet-chemical-sensor`  
  → Isolated network with dedicated subnets:  
  - `iot-devices` subnet (for sensor communication)  
  - `backend-ai` subnet (for AI processing and analysis)

- **Network Security Group**: `nsg-chemical-sensor`  
  → Controls inbound/outbound traffic with proper segmentation

### Screenshots
*(Add your screenshots here - drag and drop them into GitHub)*

1. Resource Group Overview  
2. Virtual Network with subnets  
3. IoT Hub  
4. Key Vault  

### Key Security Practices Applied
- Network segmentation between IoT devices and backend AI components
- Least-privilege networking using NSG
- Secure secret management with Azure Key Vault
- Foundation ready for Microsoft Defender for IoT and Azure Sentinel in the future

### Why This Matters for the AI Chemical Sensor Startup
This setup provides a secure, scalable cloud foundation that can safely handle sensitive chemical detection data while supporting fast AI analysis — without slowing down innovation.

Built in one afternoon using Security+ and AZ-104 knowledge.

---

**Last step for you:**

1. Go to your GitHub repo (`azure-security-portfolio`)
2. Edit the README.md file
3. Paste the text above
4. Add your screenshots (upload them and embed with `![description](screenshot-name.png)`)
5. Commit the changes

Once you’ve done that, reply with **“GitHub README done”**

Then I’ll help you prepare a short 30–60 second pitch you can use in tomorrow’s meeting when they ask about your projects or experience.

You did well today, Michael. This is way better than just showing certs.  

Ready when you are — go update the README.
