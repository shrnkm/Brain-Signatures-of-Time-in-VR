<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Supplementary Materials - Brain Signatures of Time Perception in VR</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; margin: 20px auto; width: 80%; }
        h1, h2, h3 { color: #0077b6; }
        table { width: 100%; border-collapse: collapse; margin: 20px 0; }
        table, th, td { border: 1px solid #ddd; padding: 8px; }
        th { background-color: #f2f2f2; text-align: left; }
        img, video, audio { max-width: 100%; height: auto; }
        .center { text-align: center; }
        .flex-container { display: flex; justify-content: space-between; gap: 10px; }
        .flex-container > div { width: 33%; text-align: center; }
        .flex-container-half { display: flex; justify-content: space-between; gap: 10px; }
        .flex-container-half > div { width: 48%; text-align: center; }
        caption { caption-side: top; font-weight: bold; margin-bottom: 5px; }
    </style>
</head>
<body>

    <h1>Supplementary Materials</h1>
    <h2>Brain Signatures of Time Perception in Virtual Reality</h2>

    <h3>
        <a href="https://orcid.org/0000-0002-8021-1021" target="_blank">Sahar Niknam</a>, 
        <a href="https://orcid.org/0000-0002-8691-4991" target="_blank">Saravanakumar Duraisamy</a>, 
        <a href="https://orcid.org/0000-0001-8492-7708" target="_blank">Jean Botev</a>, 
        <a href="https://orcid.org/0000-0002-5011-1847" target="_blank">Luis A. Leiva</a>
    </h3>

    <p>
        <a href="https://vrarlab.uni.lu" target="_blank">VR/AR Lab</a> & 
        <a href="https://www.uni.lu/fstm-en/research-groups/computational-interaction/" target="_blank">COIN Research Group</a>, 
        @<a href="https://www.uni.lu/en/" target="_blank">University of Luxembourg</a>
    </p>

    <hr>

    <h2>1. Study Setup</h2>
    <table>
        <tr>
            <td colspan="4"><img src="assets/study_setup_01.jpg" alt="study setup"></td>
            <td colspan="2"><img src="assets/study_setup_02.jpg" alt="study setup"></td>
        </tr>
        <tr>
            <td colspan="6" class="center"><img src="assets/study_setup_03.jpg" alt="used devices"></td>
        </tr>
        <tr>
            <td colspan="2"><img src="assets/Unicorn.png" alt="EEG cap"></td>
            <td colspan="2"><img src="assets/Leap.png" alt="Handtracker"></td>
            <td colspan="2"><img src="assets/HTC.png" alt="VR headset"></td>
        </tr>
        <tr>
            <td colspan="2" class="center">
                <a href="https://www.unicorn-bi.com/" target="_blank" style="text-decoration: underline; color: #0077b6;">
                    Unicorn Hybrid Black EEG cap
                </a>
            </td>
            <td colspan="2" class="center">
                <a href="https://www.ultraleap.com/product/" target="_blank" style="text-decoration: underline; color: #0077b6;">
                    Leap Motion Controller
                </a>
            </td>
            <td colspan="2" class="center">
                <a href="https://business.vive.com/sea/product/vive-pro-eye/" target="_blank" style="text-decoration: underline; color: #0077b6;">
                    HTC Vive Pro Eye VR headset
                </a>
            </td>
        </tr>
    </table>

    <hr>

    <h2>2. Procedure</h2>
    <div class="center">
        <img src="assets/procedure.png" alt="experiment procedure" style="width: 80%;">
        <video id="video-player" controls>
            <source src="assets/procedure.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <p>An example of an event: Cognitive modulator, Medium mode, duration 6 seconds</p>
    </div>

    <hr>

    <h2>3. Modulators</h2>
    <img src="assets/events.png" alt="5 modulators to 42 events">

    <h3>3.1. Emotion</h3>
    <!-- Emotion table retained as is -->

    <h3>3.2. Cognitive</h3>
    <div class="flex-container">
        <div>
            <img src="assets/cognitive_high.png" alt="Cognitive modulator, mode: high">
            <p>High</p>
        </div>
        <div>
            <img src="assets/cognitive_medium.png" alt="Cognitive modulator, mode: medium">
            <p>Medium</p>
        </div>
        <div>
            <img src="assets/cognitive_low.png" alt="Cognitive modulator, mode: low">
            <p>Low</p>
        </div>
    </div>

    <h3>3.3. Oddball</h3>
    <div class="flex-container">
        <div>
            <img src="assets/oddball_noOddball.gif" alt="Oddball modulator, mode: no-oddball">
            <p>No-Oddball</p>
        </div>
        <div>
            <img src="assets/oddball_relevant.gif" alt="Oddball modulator, mode: relevant oddball">
            <p>Relevant</p>
        </div>
        <div>
            <img src="assets/oddball_irrelevant.gif" alt="Oddball modulator, mode: irrelevant oddball">
            <p>Irrelevant</p>
        </div>
    </div>

    <h3>3.4. Magnitude</h3>
    <div class="flex-container">
        <div>
            <audio controls>
                <source src="assets/magnitude_highPitch.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
            <p>High pitch</p>
        </div>
        <div>
            <audio controls>
                <source src="assets/magnitude_normal.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
            <p>Normal</p>
        </div>
        <div>
            <audio controls>
                <source src="assets/magnitude_lowPitch.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
            <p>Low pitch</p>
        </div>
    </div>

    <h3>3.5. Expectation</h3>
    <div class="flex-container-half">
        <div>
            <img src="assets/expectation_slowProgressbar.gif" alt="Expectation modulator, mode: slow progressbar">
            <p>Slow progressbar</p>
        </div>
        <div>
            <img src="assets/expectation_fastProgressbar.gif" alt="Expectation modulator, mode: fast progressbar">
            <p>Fast progressbar</p>
        </div>
    </div>

    <hr>

    <h2>4. Results</h2>
    <div class="center">
        <img src="assets/topography.png" alt="Topographical map of time perception states">
        <p>Topographic map of different band powers for time perception states.</p>
    </div>
    <div class="center">
        <img src="assets/psd.png" alt="PSD plot of time perception states">
        <p>Spectral activity of EEG channels averaged over all participants, grouped by time perception states.</p>
    </div>
    <div class="center">
        <img src="assets/SNR-stats.png" alt="Time perception states statistics across 6 frequency bands">
        <p>SNR of time perception states in all EEG band powers for each participant.</p>
    </div>

    <hr>

    <h2>5. Publication</h2>
    <ul>
        <li><a href="https://this-page-intentionally-left-blank.org/" target="_blank" rel="noopener noreferrer">Link to the paper</a></li>
    </ul>

    <hr>

    <p style="text-align: left;">
        The content of this page is licensed under 
        <a href="https://creativecommons.org/licenses/by-nc/4.0/" target="_blank" rel="noopener noreferrer">
            <img src="https://licensebuttons.net/l/by-nc/4.0/88x31.png" alt="CC BY-NC 4.0 License" style="vertical-align: middle; height: 20px;">
        </a>
    </p>

</body>
</html>
