# unity-mobile-developer

![test](https://github.com/GuardianOfGods/unity-mobile-developer/assets/52252046/23f0027f-91f7-4e1b-8dc6-d7891ee60c04)

👋 **Hi there, I'm HoangVanThu**. I am currently a mobile Unity developer at a Vietnamese company. I have many years of experience in the field and I want to share what I know with everyone. 

This repository is mostly for reference, it contains the tips and tricks I have applied throughout my programming career. I hope you find it useful.

## Unity Hub
### Trouble With Liscenses
- Occasionally, adding a license in Unity Hub gets interrupted even though you have clicked to add it. My advice in this situation is to be patient and wait for a while, or you can repeatedly perform the add license action until it succeeds.

<div align="center">
<img src="https://github.com/GuardianOfGods/unity-mobile-developer/assets/52252046/1f87bd2f-bee1-4b51-9d8e-1a2d2d360f0a">
</div>

### Choose Unity Version
- First, always choose Unity versions with **LTS (Long Term Support)** to minimize errors and receive bug fixes from Unity in subsequent LTS versions.

> [!WARNING] 
> I frequently have build errors in **Xcode (iOS environment)** due to thread conflicts and library conflicts between third-party services such as Firebase, Admob, AppLovin, etc. In some cases, I have had to upgrade or downgrade Unity versions for the issue to be resolved (Unity also provides release notes to fix these errors).

<div align="center">
<img src="https://github.com/GuardianOfGods/unity-mobile-developer/assets/52252046/e830998e-a1ba-4a2c-8dbe-ac1a75ffe809">
</div>

## IDE
### Choose IDE
- There are many different IDEs that support programming in Unity. Additionally, there are many AI tools that can be integrated into IDEs, such as **Tabnine**, **Copilot**, **IntelliSense**, etc. AI can significantly boost your programming efficiency.
- Here are the three most popular and powerful IDEs that I recommend you use:
  
**1. JetBrains Rider**
- **High Performance**: Rider is known for its high performance and fast processing speed.
- **Powerful Refactoring**: Provides strong refactoring tools to improve code quality.
- **Code Analysis**: Code analysis features help detect errors and improve code.
- **Good Unity Integration**: Rider offers good integration with Unity, including debugging and code navigation.
  
**2. Visual Studio Code (VS Code)**
- **Lightweight and Flexible**: VS Code is a lightweight IDE that can be easily customized and extended with extensions.
- **Unity Extensions**: Extensions like Unity Tools and Unity Debugger enhance Unity development capabilities.
- **Supports Multiple Languages**: Supports various programming languages and frameworks, not just C#.
  
**3. Microsoft Visual Studio**
- **Good Integration with Unity**: Visual Studio provides deep integration with Unity, including debugging, code navigation, and project management.
- **IntelliSense**: Intelligent code completion helps speed up coding and reduce syntax errors.
- **Powerful Debugging Tools**: Visual Studio offers robust debugging tools that make it easy to test and fix errors.
- **Extensions and Plugins**: There are numerous extensions and plugins available to enhance the development experience.

### Attach IDE

- To attach IDE to Unity, in Unity open **Edit -> Preference -> External Tools**. Choose IDE you want to use in **External Script Editor**

<div align="center">
<img src="https://github.com/GuardianOfGods/unity-mobile-developer/assets/52252046/e3972714-fda1-45d0-90bd-6fccba3e1634">
</div>

## Unity Editor
### Unity Layout

- Here my favorite layout with 2 screens.

![image](https://github.com/GuardianOfGods/unity-mobile-developer/assets/52252046/90c041c1-dfce-40c7-aa4f-5cf625e7ff9c)

- It is not simply my preference, the logic for this layout is the convenience it provides for my workflow. I will analyze the layout to give you a clearer perspective:
1. Placing tabs within the same tab group can be time-consuming as you have to switch between tabs to display them on the screen. So I split impotant tabs to many groups.
    
![image](https://github.com/GuardianOfGods/unity-mobile-developer/assets/52252046/a5f87488-def2-4914-ac43-b1777e0fb399)

2. Viewing the information in my Hierarchy is quite easy since the two tabs are placed close to each other.

![image](https://github.com/GuardianOfGods/unity-mobile-developer/assets/52252046/9ccbfdd3-6175-4f7d-8a81-2993e3d7eb30)


3. When I need to use a prefab in the game, I can simply drag the prefab from the Project into the Hierarchy or Scene. Also, it's good for game design.

![image](https://github.com/GuardianOfGods/unity-mobile-developer/assets/52252046/dd2b1305-cab1-4afa-b32b-19dccf0fbd45)


5. While playing the game through the Game tab, I can view the information on the left side of the screen.

![image](https://github.com/GuardianOfGods/unity-mobile-developer/assets/52252046/7126b3ef-cb88-4980-8657-4efc0a0c51d2)

## Project Assets
- I usually place project-related assets in a subfolder within the **Assets** directory to easily find resources and separate them from third-party assets. 
- To display a folder at the top, I add an **"_"** to the folder name, and to display it at the bottom, I add a **"~"**.
- This image below show how I order folder assets:

![image](https://github.com/GuardianOfGods/unity-mobile-developer/assets/52252046/80db71b5-a2c3-4e58-816e-ff24cdcb56ea)




### Replace Assets

## Debug
### Debug Monitor

### Debug Logcat

## Tools

## Community

# Topics
- [Unity Mobile Optimization](https://github.com/GuardianOfGods/unity-interview-questions)
- [Unity Interview Questions](https://github.com/GuardianOfGods/unity-interview-questions)

# Support
- If you like this topic, you can give this repository a star ⭐
- I would greatly appreciate it if you could support me with a cup of coffee
<a href="https://www.buymeacoffee.com/HoangVanThu">
  <img src="https://www.the3rdsequence.com/texturedb/images/donate/buymeacoffee.svg" width="200" height="47"/>
</a>
