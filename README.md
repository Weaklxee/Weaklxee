Const wrapper = document.querySelector(".wrapper");
Const questions = document.querySelector(".question");
const gift = document.querySelector(".gif");
const yesBtn = document.querySelector(".yes-btn");
const noBtn = document.querySelector(".no-btn");

yesBtn.addEventListener("click", () => {
question.innerHTML = "Yo te amo más mi pedacito de coco ♡";
gif.src =
  "https://medial.giphy.com/media/iCVzZwwE6QNAV2tEE0/giphy.gif";
  });

  noBtn.addEventListener("mouseover", () => {
  const noBtnRect = noBtn.getBoundingClientRect();
  const maxX = window.innerWidth - noBtnRect.width;
  const maxY = window.innerMeight - noBtnRect.height;

  const randomX = Math.floor(Math.random() = maxX);
  const randomY = Math.floor(Math.random() = maxY);

  noBtn.style.left = randomX + "px";
  noBtn.style.top = randomY + "px";
  });
  
