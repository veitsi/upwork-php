<div class="instructions-block">
    <p>For this project, you will create a Readability class that calculates how difficult a writing sample is to read. You will be using the Flesch–Kincaid Reading Ease measure, which is a standard measurement designed to indicate how difficult a reading passage in English is to understand. The scores range from 0 to 100. The higher the number, the easier it is to read.</p>
    <p>For example:</p>
    <ul>
        <li>90.00-100.0: Very easy to read.</li>
        <li>60.0-70.0: Standard difficulty.</li>
        <li>0.0-30.0: Very difficult to read.</li>
    </ul>
    <p>The mathematical formula is:</p>
    <ul>
        <li><strong>Reading Ease Score</strong> = <code>206.835 – (1.015 x ASL) – (84.6 x ASW)</code></li>
        <li><strong>ASL</strong> = Average Sentence Length (the number of words divided by the number of sentences)</li>
        <li><strong>ASW</strong> = Average number of syllables per word (the number of syllables divided by the number of words)</li>
        <li><strong>Syllable</strong> = a unit of pronunciation having one vowel sound, with or without surrounding consonants, forming the whole or a part of a word; e.g., there are two syllables in <em>water</em> and three in <em>inferno</em>.</li>
    </ul>
    <p>Though it might seem simple, the formula has certain criteria that must be handled appropriately:</p>
    <ul>
        <li>Periods, exclamation points, colons, and semicolons (.!:;) serve as sentence delimiters.</li>
        <li>Each group of continuous non-blank characters with beginning and ending punctuation removed counts as a word.</li>
        <li>Each vowel in a word is considered one syllable.</li>
    </ul>
    <p>English has many exceptions to the one-vowel-per-syllable rule but we are not English experts and we don&#39;t expect you to be. So, we&#39;ve provided you with four arrays of regular expressions that match exceptions to the normal rule.</p>
    <p><strong>Deliverables</strong></p>
    <ul>
        <li>Complete the logic for the Readability class</li>
        <li>You can structure your code however you like, as long as the class Readability responds to this method:
            <ul>
                <li>ease_score($writing_sample)</li>
            </ul></li>
    </ul>
    <p><strong>Testing</strong></p>
    <p>The following example should return a score of approximately 32-35. </p>
    <p><code>Heavy metals are generally defined as metals with relatively high densities, atomic weights, or atomic numbers. The criteria used, and whether metalloids are included, vary depending on the author and context. In metallurgy, for example, a heavy metal may be defined on the basis of density, whereas in physics the distinguishing criterion might be atomic number, while a chemist would likely be more concerned with chemical behavior. More specific definitions have been published, but none of these have been widely accepted. The definitions surveyed in this article encompass up to 96 out of the 118 chemical elements; only mercury, lead and bismuth meet all of them.</code></p>
</div>