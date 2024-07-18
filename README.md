# sitetositevpn
site-to-site connectivity
I worked on an intriguing project: site-to-site VPN connectivity 🔐.

A site-to-site VPN allows you to securely connect your on-premises network to your Azure virtual network. This is essential for seamless integration, ensuring secure data transfer, and extending your network to the cloud.

🔗 Processes of Connectivity:

      Created an Azure Virtual Network: Added an address space and subnets.
     Local Network Gateway: Represented the on-premises network by 
     specifying the VPN device’s IP address and local network prefixes.
    Public IP: Required for the Azure VPN gateway to establish the connection.
     Configured Gateway Subnet: Set up the VPN gateway in Azure.

🛠 Setting up the On-Premises VPN Device:


   Configured the local VPN device to connect to Azure using IPsec/IKE 
 protocols.
 
     Connected the Azure virtual network gateway to the local network gateway
 using a shared key.
 
     Ensured the VPN connection showed as "Connected" in the Azure portal.
