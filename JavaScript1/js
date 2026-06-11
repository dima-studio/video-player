const video = document.getElementById("myVideo");
const playPauseBtn = document.getElementById("playPauseBtn");
const muteBtn = document.getElementById("muteBtn");

playPauseBtn.addEventListener("click", function ()
{

    if (video.paused)
    {
        video.play();
        playPauseBtn.textContent = "Pause";
    }

    else
    {
        video.pause();
        playPauseBtn.textContent = "Play";
    }

});

muteBtn.addEventListener("click", function ()
{

    if (video.muted)
    {
        video.muted = false;
        muteBtn.textContent = "Mute";
    }

    else
    {
        video.muted = true;
        muteBtn.textContent = "Unmute";
    }

});
