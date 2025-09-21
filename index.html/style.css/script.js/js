// 🌱 Floating Leaves Animation for Ar-Raudah Foundation
document.addEventListener("DOMContentLoaded", () => {
  const body = document.body;

  function createLeaf() {
    const leaf = document.createElement("div");
    leaf.classList.add("leaf");
    leaf.textContent = "🍃";

    // Random position and size
    leaf.style.left = Math.random() * window.innerWidth + "px";
    leaf.style.fontSize = Math.random() * 20 + 20 + "px";

    body.appendChild(leaf);

    // Remove leaf after 10s
    setTimeout(() => {
      leaf.remove();
    }, 10000);
  }

  // Generate leaves every 700ms
  setInterval(createLeaf, 700);

  // 🌳 Interactive: Click to plant a “tree”
  body.addEventListener("click", (e) => {
    const tree = document.createElement("div");
    tree.classList.add("tree");
    tree.textContent = "🌳";

    tree.style.left = e.pageX - 20 + "px";
    tree.style.top = e.pageY - 20 + "px";

    body.appendChild(tree);

    setTimeout(() => {
      tree.remove();
    }, 5000);
  });
});
