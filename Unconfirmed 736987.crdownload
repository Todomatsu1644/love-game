document.addEventListener('DOMContentLoaded', () => {
    const yesBtn = document.getElementById('yesBtn');
    const noBtn = document.getElementById('noBtn');
    const answerDiv = document.getElementById('answer');

    yesBtn.addEventListener('click', () => {
        answerDiv.innerText = 'I love you too!';
    });

    noBtn.addEventListener('mouseover', () => {
        const container = document.querySelector('.container');
        const containerRect = container.getBoundingClientRect();
        const noBtnRect = noBtn.getBoundingClientRect();

        let newTop = Math.random() * (containerRect.height - noBtnRect.height);
        let newLeft = Math.random() * (containerRect.width - noBtnRect.width);

        noBtn.style.position = 'absolute';
        noBtn.style.top = `${newTop}px`;
        noBtn.style.left = `${newLeft}px`;
    });
});