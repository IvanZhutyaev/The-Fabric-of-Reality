# **The Fabric of Reality**  
**A surreal horror-puzzle game where reality unravels at the seams.**  

[![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-5.3+-black.svg?logo=unrealengine)](https://www.unrealengine.com)  
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)  

## **🌌 Overview**  
Step into the decaying **Linenberg Asylum**, where the fabric of reality is tearing apart. As **The Tailor**, wield the **Reality Needle** to stitch together collapsing space, solve perspective-bending puzzles, and uncover the horrifying truth behind the experiments that shattered existence.  

---

## **📜 Story**  
Explore the abandoned asylum where Dr. Elias Varg conducted experiments to "rewrite reality". Discover:  
- **Audio logs** revealing the truth about the "Thread" experiments  
- **Multiple endings** based on your final choice: restore or destroy reality  
- **Environmental storytelling** through shifting architecture and patient notes  

*"The last stitch holds the world together..."*  

---

## **🎮 Key Features**  
| Feature | Description |  
|---------|-------------|  
| **Reality-Stitching** | Physically sew objects/space together with the Reality Needle |  
| **Perspective Puzzles** | Change object properties by viewing them from different angles |  
| **Dynamic Decay** | Watch as the asylum transforms into surreal configurations |  
| **Enemy System** | Fight or outsmart entities born from reality tears |  

---

## **🛠️ Technical Implementation**  
### **Engine & Tools**  
- **Unreal Engine 5.3+** (Nanite/Lumen enabled)  
- **Blueprints** (Primary gameplay scripting)  
- **C++** (Core systems)  
- **Niagara** (Reality-tear VFX)  
- **MetaSounds** (Dynamic audio)  

### **Project Structure**  
```  
Content/  
├─ Blueprints/  
│  ├─ Gameplay/        # Player mechanics, Reality Needle system  
│  ├─ AI/              # Enemy behaviors  
│  └─ UI/              # Widget interactions  
├─ Levels/  
│  ├─ Asylum/          # Modular level pieces  
│  └─ Prototypes/      # Test environments  
├─ Assets/  
│  ├─ Characters/      # Skeletal meshes and animations  
│  ├─ Effects/         # Niagara systems for reality tears  
│  └─ Materials/       # Dynamic material instances  
Source/  
└─ FabricOfReality/    # C++ modules for core systems  
```  

---

## **👾 Enemy Types**  
| Type | Behavior | Counterplay |  
|------|----------|-------------|  
| **Seams** | Chase along stitched paths | Sew their bodies shut |  
| **Eyes** | Amplify distortions when seen | Avoid direct eye contact |  
| **Shadows** | Emerge from floor tears | Stitch tears to trap them |  

---

## **🚀 Getting Started**  
### **Requirements**  
- **OS:** Windows 10/11 (DirectX 12)  
- **CPU:** Intel i7 / Ryzen 7  
- **GPU:** RTX 2060+ (for Lumen/Nanite)  
- **RAM:** 16GB+  

### **Setup**  
1. Clone with Git LFS:  
   ```bash  
   git clone https://github.com/IvanZhutyaev/The-Fabric-of-Reality.git 
   ```  
2. Enable plugins:  
   - Niagara  
   - MetaSounds  
   - Chaos Cloth  

---

## **🗺️ Development Roadmap**  
- **Q2 2025:** Core mechanics prototype  
- **Q4 2025:** Vertical slice (Reception area)  
- **Q2 2026:** Full asylum + all endings  

---

## **🤝 Contributing**  
1. Fork the repository  
2. Create your feature branch (`git checkout -b feature/amazing-feature`)  
3. Commit changes (`git commit -m 'Add some feature'`)  
4. Push to the branch (`git push origin feature/amazing-feature`)  
5. Open a Pull Request  

**Coding Standards:**  
- **Blueprints:** Use event dispatchers for cross-system communication  
- **C++:** Follow Epic's coding conventions  
- **Assets:** Prefix with type (e.g., `BP_RealityNeedle`)  

---

## **📜 License**  
MIT License - See [LICENSE](LICENSE) for details.  

---

## **🌟 Credits**  
- **Lead Developer:** Ivan Zhutyaev 
- **Concept Artist:** Vasily Zadorozhny
- **Sound Design:** Ashot Oganesyan  
- **Inspired By:** *Control, Silent Hill, Superliminal*  

---

**🪡 Crafted with Unreal Engine 5 and unraveling sanity.**  

---

### **Key Alignment with TZ:**  
1. **Full story integration** (Dr. Varg, experiments, multiple endings)  
2. **All gameplay mechanics** from TZ are documented  
3. **Technical specs** match original requirements  
4. **Enemy types** fully detailed  
5. **Roadmap** reflects TZ development phases  

Need any additional adjustments?
