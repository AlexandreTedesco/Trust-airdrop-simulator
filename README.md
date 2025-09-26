
# $TRUST Airdrop Simulator

Interactive simulator for the Vibe Coding Contest - Calculate your potential $TRUST airdrop based on your IQ points and Relics collection.

## 🚀 Features

- **Real-time calculation** with transparent step-by-step breakdown
- **Relic bonus system** with fixed IQ bonuses per rarity
- **Collection bonuses** for having multiple rarities (2R to 6R)
- **Visual Relic interface** with images and counters
- **Responsive design** optimized for all devices

## 📊 How it works

### Calculation Formula
1. **Base tokens** = (Your IQ ÷ Total IQ) × Airdrop Pool
2. **Add Relic bonuses** to your IQ
3. **Apply collection bonus** (2+ rarities)
4. **Final tokens** = (Effective IQ ÷ Total IQ) × Pool

### Relic Bonuses
- ✨  **Common**: +10k IQ
- ✨  **Rare**: +20k IQ  
- ✨  **Epic**: +50k IQ
- ✨  **Legendary**: +100k IQ
- ✨  **Ancient**: +200k IQ
- ✨ **Mystic**: +500k IQ

### Collection Bonuses
- **2 rarities**: +10k IQ
- **3 rarities**: +25k IQ
- **4 rarities**: +50k IQ
- **5 rarities**: +100k IQ
- **6 rarities**: +200k IQ

## 🛠️ Setup Instructions

1. **Open VSCode** and extract this folder
2. **Install dependencies**:
```bash
npm install
```
3. **Start local server**:
```bash
npm start
```
4. **Open browser** and navigate to `http://localhost:8000`

## 🎯 Usage

1. **Enter your base IQ points** (default: 17,000,000)
2. **Configure airdrop parameters**:
   - Airdrop pool (default: 200M TRUST)
   - TGE price (default: $0.25)
   - Total IQ in circulation (default: 100B)
3. **Select your Relics** by entering quantities for each rarity
4. **View results** with detailed calculation breakdown

## 📁 Project Structure

```
TRUST_Airdrop_Simulator_VSCode/
├── index.html          # Main simulator file
├── package.json        # Dependencies and scripts
├── README.md          # This file
└── asset/             # Relic images
    ├── common.png
    ├── rare.png
    ├── epic.png
    ├── legendary.png
    ├── ancient.png
    └── mystic.png
```

## ⚠️ Disclaimer

This is a **speculative simulator** for educational purposes. All values (total IQ circulation, airdrop pool, TGE price) are **estimates only** and not official data.

## 🏆 Contest Submission

Ready for the Vibe Coding Contest! The simulator includes:
- ✅ Live hosted URL capability
- ✅ Transparent calculation methodology
- ✅ User-friendly interface
- ✅ Educational value

---

**Built for the $TRUST Airdrop Simulator Vibe Coding Contest** 🚀
