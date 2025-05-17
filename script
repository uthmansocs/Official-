const yesBtn = document.getElementById("yesBtn");
const noBtn = document.getElementById("noBtn");
const response = document.getElementById("response");
const container = document.querySelector(".container");

yesBtn.onclick = () => {
  // Fade out the question and buttons
  container.classList.add("fadeOut");

  // Delay before showing love message
  setTimeout(() => {
    document.body.innerHTML = `
      <div class="love-message">
        <p>
        My Love,<br><br>

        I don’t even know where to start, because words feel so small compared to the way I feel about you. But I’ll try — not because I have to, but because you deserve to hear it, in every way I can possibly say it.<br><br>

        You mean <strong>so much</strong> to me. I hope you truly know that. You’re not just a part of my life — you’ve become the best, most beautiful part of it. You’re not just my girlfriend, you’re my safe space, my peace, my motivation, and honestly, the person who makes all the chaos in the world feel just a little more bearable.<br><br>

        I love the way you talk, the way you laugh, the way you say my name like it actually matters. I love the way you care, even in the tiniest of things — like checking in on me when I’m stressed, sending me things that remind you of us, or just being present. I don’t know how you do it, but every time we talk, I feel like I’m being seen. Really seen. And that’s such a rare and beautiful thing.<br><br>

        You’ve been there for me in ways I don’t even know how to explain. On the days when I’ve doubted myself, you’ve believed in me. When I felt empty, you filled that space with your light. When I felt alone, you stayed. That kind of love? It’s not something I take for granted. Not even for a second.<br><br>

        You’ve made me want to be a better person — not out of pressure, but out of love. Because I want to give you the kind of love you give me: honest, deep, loyal, soft, and strong at the same time. You’ve made me realize that love isn’t just about flowers and sweet words (though I hope I give you plenty of both) — it’s about showing up, holding space, and being someone you can rely on. And I promise you, I’m always going to show up for you. In every way I can. Through every high and low.<br><br>

        I’ve fallen for the real you — your smile, your moods, your dreams, your flaws, your heart, your mind — all of it. And I’m still falling, deeper and deeper, with every conversation, every silence, every laugh, every moment. You’re everything I didn’t know I needed. You complete spaces in me I didn’t even know were empty.<br><br>

        Sometimes I lie awake thinking about how lucky I am. How blessed I am to call you mine. And no matter where life takes us, I want you to always remember this: you are deeply loved. You are valued. You are appreciated. Not just for what you do, but for <strong>who you are</strong>.<br><br>

        So when you’re tired, or overwhelmed, or questioning your worth — remember this message. Remember <strong>me</strong>. And know that there’s someone who sees your light even on your darkest days. Someone who isn’t going anywhere. Someone who loves you, fully and completely.<br><br>

        Thank you for being mine.<br>
        Thank you for choosing me.<br>
        Thank you for <strong>being you</strong>.<br><br>

        With all my heart,<br>
        Yours — now, always, and in every little forever we get to build together.<br><br>

        — <strong>I LOVE YOU</strong>
        </p>
      </div>
    `;
    createHearts();
  }, 1000);
};

noBtn.onmouseover = () => {
  const offsetX = Math.floor(Math.random() * 300) - 150;
  const offsetY = Math.floor(Math.random() * 300) - 150;
  noBtn.style.transform = `translate(${offsetX}px, ${offsetY}px)`;
};

// Floating hearts
function createHearts() {
  setInterval(() => {
    const heart = document.createElement('div');
    heart.classList.add('heart');
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.animationDuration = Math.random() * 2 + 3 + "s";
    heart.innerText = "💗";
    document.body.appendChild(heart);
    setTimeout(() => heart.remove(), 5000);
  }, 300);
}
