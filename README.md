# InfraMap
Mobile App in React Native aiming the network infrastructure documentation

#Platforms:
- Use Google Firebase API for storage
- User React Native
- Use Google Drive API

#App overview:
- Add a Company: corporation/customer in the app, it will create a folder in google drive with it's name
- Add an Equipment Room to a Company: it will create a folder in google drive with it's name
- Add a Telecommunication Closet to an ER: it will create a folder in google drive with it's name
- Add a Device to a TC: or equipment, it will create MyDevice.json in google drive with it's name
- Add physical interface to a Device: append to MyDevice.json, you can choose:
  * Set name
  * Set model (string base, maybe pre defined)
  * Set type (pre defined: Ethernet, GigabitEthernet, SFP, SFP+, wlan)
  * Set link (to another device, must show the target(er+tc+dev+interface)
