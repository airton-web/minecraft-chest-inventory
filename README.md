# 🧱 Minecraft Web Inventory UI

A fully interactive **Minecraft-inspired inventory system** built with pure HTML, CSS, and JavaScript.
This project simulates core inventory mechanics such as item stacking, splitting, and cursor interaction — all inside a web environment.

---

## 🚀 Features

* 🎮 Minecraft-style UI and layout
* 📦 Real inventory grid (9x3 chest)
* 🖱️ Drag & drop item system
* ➕ Stack merging with limits
* ✂️ Right-click split stacks
* 👤 Player head with external link
* 🧰 Multiple item types (64 / 16 / 1 stack sizes)
* 🎨 Vanilla-style container texture
* 📛 Dynamic inventory title (`Chest of {player}`)
* ❌ Close button + ESC support
* 🧊 Pixel-perfect rendering

---

## 🎥 GIF Preview

![Inventory Preview](preview.gif)

> 💡 Tip: Record your screen using tools like OBS Studio or ScreenToGif and export as `preview.gif`
> Then place it in your project root folder.

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla)
* Minecraft asset textures

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/minecraft-web-inventory.git
```

2. Open the project folder:

```bash
cd minecraft-web-inventory
```

3. Run the project:

* Just open `index.html` in your browser

---

## 🎨 Assets

Make sure you have these files in your project folder:

* `container.png` → Inventory background
* `chest.png` → Chest image
* `fundo.png` → Background

You can use Minecraft assets from:
https://github.com/InventivetalentDev/minecraft-assets

---

## 🎮 Controls

| Action        | Behavior                      |
| ------------- | ----------------------------- |
| Left Click    | Pick up / place / merge items |
| Right Click   | Split stack / place one item  |
| ESC           | Close inventory               |
| Click on Head | Opens GitHub profile          |

---

## 🧠 How It Works

* Inventory is stored in a JavaScript array
* Each slot contains:

```js
{
  img: "url",
  count: number,
  max: number
}
```

* Cursor acts as a temporary item holder
* Rendering is fully dynamic via DOM updates

---

## 📌 Future Improvements

* 🔄 Shift-click (quick move)
* 🖱️ Drag selection
* 🧾 Tooltips (item names & rarity)
* 🔊 Sound effects (open/close chest)
* 🎞️ Chest opening animation
* 🧩 Backend integration (API / database)

---

## 🤝 Contributing

Pull requests are welcome.
If you want to improve the system, feel free to fork and submit ideas.

---

## 📄 License

This project is for educational purposes.
Minecraft assets belong to Mojang.

---

## ⭐ Support

If you liked this project, consider giving it a ⭐ on GitHub!
