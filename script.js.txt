const btn = document.getElementById('passionBtn');
const message = document.getElementById('message');

btn.addEventListener('click', () => {
    if (message.style.display === 'none') {
        message.style.display = 'block';
    } else {
        message.style.display = 'none';
    }
});
