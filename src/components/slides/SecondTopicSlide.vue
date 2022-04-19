<template>
    <section data-auto-animate>
        <h4>Can we show that atoms only accept quantized energy amounts?</h4>
        <p>and</p>
        <h4>Can we determine the value of Mercury's first excitation level?</h4>
        <div class="mt-20"></div>
        <p class="fragment">Yes, we can. However, before we show that, let's talk about the procedure for performing the experiment.</p>
    </section>
    <section data-auto-animate>
        <h3>Experimental Design &ndash; Oven Settings</h3>
        <div class="flex justify-center items-center flex-col">
            <img src="@/images/oven-settings.png" alt="Oven Settings" />
        </div>
    </section>
        <section data-auto-animate>
        <h3>Experimental Design<br />V<sub>a</sub>, V<sub>r</sub>, &amp; Filament Settings</h3>
        <div class="flex justify-center items-center flex-col">
            <img src="@/images/va_vr_filament_settings.png" alt="Va, Vr, and Filament Settings" />
        </div>
    </section>
        <section data-auto-animate>
        <h3>Experimental Design &ndash; Data View</h3>
        <div class="flex justify-center items-center flex-col">
            <img src="@/images/data_settings.png" alt="Data Settings" />
        </div>
    </section>
    <section data-auto-animate>
        <h3>Experimental Procedure</h3>
        <p>The experiment is actually fairly simple, but it is tedious. It consists of the following setup steps:</p>
        <ol>
            <li class="fragment">Heat up the oven to 180&deg;C. <strong>This takes a long time.</strong></li>
            <li class="fragment">Turn on and zero-check the electrometer.</li>
            <li class="fragment">Reset the filament variac and turn on the power source.</li>
            <li class="fragment">Set the retarding potential to 1.3 volts.</li>
            <li class="fragment">Set the V<sub>a</sub> potentiometer to 40 volts.</li>
        </ol>
        <p class="fragment">At this point, all the equipment is functioning. We can now begin the actual experiment.</p>
    </section>
    <section data-auto-animate>
        <h3>Experimental Procedure</h3>
        <p>After all the equipment is functioning, data-collection is a simple but repetitive task consisting of the following:</p>
        <ol>
            <li class="fragment">Decrease the V<sub>a</sub> potentiometer by a small amount (3.6&deg; adjustment), starting from 40 volts</li>
            <li class="fragment">Allow the electrometer to settle upon a new current measurement</li>
            <li class="fragment">Record the values of V<sub>a</sub> and the measured current.</li>
            <li class="fragment">Repeat eighty times.</li>
        </ol>
    </section>
    <section data-auto-animate>
        <h3>Results of Data Collection</h3>
        <div class="flex justify-center items-center">
            <img class="fullimg" src="@/images/i-va-chart.png" alt="Current vs voltage chart" />
        </div>
    </section>
    <section data-auto-animate>
        <h3>Results of Data Collection</h3>
        <div class="flex justify-center items-center">
            <img class="fullimg" src="@/images/i-va-chart-2.png" alt="Current vs voltage chart" />
        </div>
    </section>
    <section data-auto-animate>
        <h3>Results of Data Collection</h3>
        <p>As discussed, the graph measured voltage differences between each current peak. Each peak was relatively close together. I found a 4.5V and 5.0V difference twice each, and a 5.5V difference once.</p>
        <p class="fragment">Per Franck and Hertz, the difference we expect each time is 4.9V. The reason for the discrepancies in my values will be explored near the end of the presentation.</p>
        <p class="fragment">For reporting purposes, I will take the average of my voltage results as the difference between each peak: $\frac{2*4.5 + 2*5.0 + 5.5}{5} = 4.9V$. Interestingly, the average exactly matches theory.</p>
    </section>
</template>

<style scoped>
img {
    height: 500px;
}

img.fullimg {
    height: auto;
}
</style>