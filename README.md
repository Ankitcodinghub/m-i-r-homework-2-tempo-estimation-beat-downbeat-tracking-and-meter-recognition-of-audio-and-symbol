# m-i-r-homework-2-tempo-estimation-beat-downbeat-tracking-and-meter-recognition-of-audio-and-symbol
**TO GET THIS SOLUTION VISIT:** [M.I.R Homework 2-Tempo estimation, beat/downbeat tracking, and meter recognition of audio and symbol](https://www.ankitcodinghub.com/product/m-i-r-homework-2-tempo-estimation-beat-downbeat-tracking-and-meter-recognition-of-audio-and-symbolic-data-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98938&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;M.I.R Homework 2-Tempo estimation, beat\/downbeat tracking, and meter recognition of audio and symbolic data Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Homework 2

Tempo estimation, beat/downbeat tracking, and meter recognition of audio and symbolic data

In this assignment we will need to accomplish the following tasks: (1) compute the tempo of a song, (2) identify every beat/downbeat position of a song, and (3) identify the meters of a song.

The definitions of beat and downbeat have been mentioned in the course slides. Meter refers to the regularity of repeating patterns of music. In a narrow sense, meter here refers to the relationship between beats and bars. For example, time signature 3/4 means that each bar contains 3 beats, and each beat is a quarter note; therefore, its meter is 3-beats. The commonly seen meters in our everyday music are 3-beats, 4-beats or their multiples, while 5-beats and 7-beats are also used sometimes.

In this assignment, we will run five datasets. They are:

<ul>
<li> &nbsp;ISMIR2004 (tempo)</li>
<li> &nbsp;Ballroom (tempo, beat, downbeat)</li>
<li> &nbsp;SMC(beat)</li>
<li> &nbsp;JCS (beat, downbeat, meter)</li>
<li> &nbsp;ASAP (beat, downbeat, meter)

These datasets are available here (our TA have dealt with most of the label files for you): (Ballroom), (JCS), (Other three datasets)You might also need to use the following functions in librosa:  librosa.feature.fourier_tempogram

 librosa.feature.tempogram

 librosa.beat.tempo

 librosa.beat.beat_track

 librosa.tempo_frequencies

 librosa.fourier_tempo_frequencies

And maybe others. Read the documentation of librosa carefully and discover the useful functions by yourself. Also, you can choose to implement the tempograms and the related features by yourself.

Task 1: tempo estimation

Q1 (20%): Design an algorithm that estimate the tempo for the ISMIR2004 and the Ballroom dataset. Assume that the tempo of every clip is constant. Note that your algorithm should output two
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
predominant tempi for each clip: 𝑇 (the slower one) and 𝑇 (the faster one). For example, you may 12

simply try the two largest peak values in the tempogram over the whole clip. Please compare and discuss the results computed from the Fourier tempogram and the autocorrelation tempogram.

The evaluation metrics of tempo estimation is as follows. We need to compute a “relative saliency of 𝑇 ” defined by the strength of 𝑇 relative to 𝑇 . It is to say, for the tempogram 𝐹(𝑡, 𝑛), we have the

</div>
</div>
<div class="layoutArea">
<div class="column">
112

</div>
</div>
<div class="layoutArea">
<div class="column">
saliency 𝑆 =𝐹(𝑇,𝑛)/(𝐹(𝑇,𝑛)+𝐹(𝑇,𝑛)) for tempo value 𝑡 at a specific time at n. For an 1112

excerpt with ground-truth tempo G, the P-score of the excerpt is defined as 𝑃=𝑆𝑇 +(1−𝑆)𝑇

</div>
</div>
<div class="layoutArea">
<div class="column">
0 otherwise

Another score function is the “at least one tempo correct” (ALOTC) score, defined as

</div>
</div>
<div class="layoutArea">
<div class="column">
1 𝑡1 1 𝑡2 𝐺−𝑇

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑇 ={1 if| 𝑖|≤0.08,𝑖=1,2 𝑡𝑖 𝐺

</div>
</div>
<div class="layoutArea">
<div class="column">
𝐺−𝑇 𝐺−𝑇

𝑃={1 if | 1|≤0.08or | 2|≤0.08

</div>
</div>
<div class="layoutArea">
<div class="column">
𝐺𝐺 0 otherwise

</div>
</div>
<div class="layoutArea">
<div class="column">
Compute the average P-scores and the ALOTC scores of the ISMIR2004 dataset and the eight genres (Cha Cha, Jive, Quickstep, Rumba, Samba, Tango, Viennese Waltz and Slow Waltz) in the Ballroom dataset using your algorithms. The above process can all be found in the evaluation routine mir_eval.tempo.detection.

Note 1: if you want to use librosa.beat.tempo directly, you have to find some ways to let it output two tempi.

Q2 (20%): Instead of using your estimated [𝑇 , 𝑇 ] in evaluation, try to use [𝑇 /2, 𝑇 /2] , 12 12

[𝑇 /3, 𝑇 /3], [2𝑇 , 2𝑇 ], and [3𝑇 , 3𝑇 ] for estimation. What are the resulting P-score values? Also, 121212

compare and discuss the results using the Fourier tempogram and the autocorrelation tempogram.

Q3 (20%): The window length is also an important factor in tempo estimation. Try to use 4s, 6s, 8s, 10s, 12s for both Fourier tempogram and the autocorrelation tempogram and compare the ALOTC of the eight genres in the Ballroom dataset and ISMIR2004 dataset.

Task 2: using dynamic programming for beat tracking

Q4 (20%): Using librosa.beat.beat_track to find the beat positions of a song. Evaluate this beat tracking algorithm on the Ballroom dataset. The F-score of beat tracking is defined as 𝐹 ≔ 2𝑃𝑅/(𝑃 + 𝑅), with Precision, P, and Recall, R, being computed from the number of correctly detected onsets TP, the number of false alarms FP, and the number of missed onsets FN, where 𝑃 ≔

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
𝑇𝑃/(𝑇𝑃 + 𝐹𝑃) and 𝑅 ≔ 𝑇𝑃/(𝑇𝑃 + 𝐹𝑁). Here, a detected beat is considered a true positive when it is located within a tolerance of ±70 ms around the ground truth annotation. If there are more than one detected beat in this tolerance window, only one is counted as true positive, the others are counted as false alarms. If a detected onset is within the tolerance window of two annotations, then one true positive and one false negative will be counted. This process can be done with mir_eval.beat. Similarly, please compute the average F-scores of the eight genres in the Ballroom dataset and discuss the results.

Q5 (20%) Also use this algorithm on the SMC, JCS, and ASAP datasets. Compare and discuss the results together with the results of the Ballroom dataset. Could you explain the difference in performance?

Note: since these datasets are large, please run these datasets as early as possible in order not to be late in submitting your homework.

Task 3: meter recognition (bonus)

Q6 (20%): The meter of a song can be 2-beats, 3-beats, 4-beats, 5-beats, 6-beats, 7-beats, or others. There might be multiple meters existing in a song (e.g., a 4-beats section followed by a 3-beats section). As a task combining both beat tracking and downbeat tracking, meter recognition is still a challenging task. Could you design an algorithm to detect the instantaneous meter of a song? Test the algorithm on the clips in the JCS dataset, and report frame-wise accuracy. The 1, 2, 3, 4, 5 after every line in the annotation file is the meter annotation. You can simply use madmom.features.beats (the state- of-the-art beat tracker) or combine other functions mentioned above.

The deadline for this homework is June 7 (Tue).

</div>
</div>
</div>
