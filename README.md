# FortiSOAR – Kaspersky Security Center Integration Issue Report

Kaspersky Security Center makes it easy to manage and secure both physical and virtual endpoints from a single, unified management console.

This FortiSOAR connector enables seamless integration with Kaspersky Security Center to:

✅ Query if a specific host exists in Kaspersky Security Center (KSC)

✅ Retrieve basic information about that host

⚠️ The connector itself have issue. Make sure user have the sufficient user role permissions in Kaspersky.

🐞 Reported Issue
🔐 Access Denied – Error Code 1184


{
  "code": 1184,
  "message": "Access denied",
  "module": "KLSTD"
}
✅ This connector resolves the above issue by ensuring proper handling of Kaspersky API permissions and user roles.

🔗 Connector File: kaspersky-security-center_ikram.tgz
📥 You can use this file to connect FortiSOAR with Kaspersky — simply upload it in FortiSOAR > Connectors section.


