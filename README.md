# base
billion-Agent-Identity-command (On Termux App)
🚀 Verified Agent Identity Setup (Step-by-Step Guide)
🟢 Step 1: Update & Upgrade Packages
pkg update && pkg upgrade
🟢 Step 2: Install Node.js
pkg install nodejs
🟢 Step 3: Install Git
pkg install git
🟢 Step 4 (Optional): Check Node.js Version
node -v
🟢 Step 5: Clone the Repository
git clone https://github.com/BillionsNetwork/verified-agent-identity
🟢 Step 6: Open Project Folder
cd verified-agent-identity
🟢 Step 7: Install Required Dependencies
npm install shell-quote @iden3/js-iden3-auth @0xpolygonid/js-sdk ethers uuid cross-fetch
🟢 Step 8: Install Clawhub Setup
npx clawhub@latest install verified-agent-identity
🟢 Step 9: Create New Ethereum Identity
node scripts/createNewEthereumIdentity.js
🟢 Step 10: Link Human to Agent
node scripts/manualLinkHumanToAgent.js --challenge '{"name":"YourAgent","description":"AI agent"}'
done all
