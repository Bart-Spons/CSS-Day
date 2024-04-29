<h1>CSS Day Hackathon Challenge</h1>

<p>The 10th edition of CSS Day is coming up, and we plan to design something special for the website for this occasion. We are completely free to use existing data and design/develop as we wish. Of course, it is important that it is not a static webpage with text everywhere but something out-of-the-box. We have three days to deliver a product in teams. To make it even more exciting, the winning team will receive tickets for this year's CSS Day.</p>

<img width="400" src="https://github.com/AliAhmed205/hackathon2324/assets/118130116/e6f85ea8-e8e6-412f-adca-5c9a976a55dd">
<br><br>
<img width="200" src="https://github.com/AliAhmed205/hackathon2324/assets/118130116/17377bb6-73ab-4ced-aaac-08a3f6e1bc64">
<br><br>
<h3>25/03/2024</h3>
<!-- <img width="400" src="https://github.com/AliAhmed205/hackathon2324/assets/118130116/f814356b-1b8a-4a73-9919-fb03e4d5ddeb"> -->

<p>After the lecture by Krijn, we immediately started brainstorming. We considered which data we wanted to present and how we could design it in an attractive way. We made some sketches and analyzed existing media products, such as Spotify Wrap or YouTube Rewind. We looked at different platforms that provide a summary of the use of a specific topic throughout the year.</p>

<!-- <img width="250" src="https://github.com/AliAhmed205/hackathon2324/assets/118130116/6ab95b13-d149-4d07-9b45-3cd3acd54efc"> -->

<h2>The Data </h2>
<p>We have gone through the .JSON file and analyzed various data types, including speakers, associated videos, the number of views, the involved countries, and the number of visitors. With this data as a starting point, we strive to create a coherent whole that not only accurately represents the data, but also looks unique and creative. We have chosen the following data types with which we could potentially work:</p>

<ul>
  <li>Speakers</li>
  <li>Visitors</li>
  <li>Views</li>
  <li>Year</li>
  <li>Color</li>
</ul>
<br>
<img width="700" src="https://github.com/AliAhmed205/hackathon2324/assets/118130116/ecc144af-61d4-4763-8388-4397279229a0">

<p>Data blobs are pieces of information where each 'blob' contains data from the .JSON file. The size of these blobs varies per year, depending on factors such as the number of treatments of specific topics. They also move on the interface and float in different directions. But there are also drawbacks. How should mobile users navigate? Should they click first to understand what the blob is about?</p>
<img width="696" src="https://github.com/AliAhmed205/hackathon2324/assets/118130116/264308f4-1f2c-4ee6-a6cf-fc220c178a64">

<br><br>
<img width="700" src="https://github.com/AliAhmed205/hackathon2324/assets/118130116/5ace56f5-3ab7-4f6e-af26-cebb129cddc6">

<p>With the CSS-SLOTMACHINE, the user can pull the lever to generate a combination that then adjusts the user interface based on the provided information. Although it may seem purely coincidental at first glance, everything is actually interconnected, creating an illusion for the user. The three options are: the year, the speaker, and possibly the number of views or another data object. These three items are interconnected, but we will implement it so that it appears as if everything is randomly arranged, while in reality, there is an algorithm behind it.</p>

<img width="864" src="https://github.com/AliAhmed205/hackathon2324/assets/118130116/0a4912d4-5ba5-4b13-9e8e-9a81eba0bbad">

<h2>Next Steps</h2>

<p>After discussing what seemed most effective, we preferred the CSS Slotmachine. Now we had to decide what would happen next. The user pulls the lever of the slot machine, but what happens next? Does the user interface change completely? Does it scroll down somewhere or are we led to a different page? This was the next step in our process, so we decided to sketch some more ideas.</p>
<br>
<img width="500" src="https://github.com/AliAhmed205/hackathon2324/assets/118130116/f1270ba3-81a0-46c7-8b8d-96a51b6f0156">
<img width="500" src="https://github.com/AliAhmed205/hackathon2324/assets/118130116/34d8a6ea-0edb-417c-a62a-e7523d985e09">
<br><br>
<!-- <img width="500" src="https://github.com/AliAhmed205/hackathon2324/assets/118130116/c71f69c2-ba4d-407d-8777-f40760bfbcce"> -->

<h1>What has everyone done for this project?</h1>

<h2>Ali</h2>

<h3>25/03/2024</h3>
<p>On Monday, I immediately started writing the HTML. I already had a good idea of how the logo should appear on screen through animations. I split "CSS" and "Day" in two, and in between would be the slot machine that Kevin was working on. Initially, everything was smooth, but I also wanted it to be responsive, so I changed "display: flex" to "display: grid".</p>

<h2>Kevin</h2>

<img width="400" src="https://github.com/AliAhmed205/hackathon2324/assets/118130116/7ce1b21c-de34-4485-bd96-7fafc1e53e07">

<p>On Monday, I was mainly involved in coming up with and sketching ideas that came to mind, to visually see how it would look. Additionally, we went through the data to look for interesting angles. I was also busy trying to make the slot machine 3D and made the lever that made the slot machine spin.</p>

<h3>Challenges</h3>
<p>Making the slot machine 3D was not so easy to do. With an earlier example that Sanne had made during the lesson, I tried this, but the annoying thing was that not every "slot" could have the same number of items in it. For example, there were 20 countries and only 10 colors. Therefore, we dropped the idea of making the slot machine 3D for a while and first focused on making a "flat" slot machine.</p>

<h3>26/03/2024</h3>
<p>On Tuesday, I tried once more to make the slot machine 3D. I got further this time but still ran into problems that caused me to lose too much time. I also set up an XD prototype for the process so that the operation we wanted to achieve was clear. In the afternoon, I merged my branch with Ali's, which meant the "top part" of our idea was quite finished.</p>

<h3>Challenges</h3>
<p>After I merged with Ali and my branch, we had some problems with scaling the slot machine, it had to be responsive! I asked Sanne for help, and she made a different setup on how to randomly spin the slot machine, solving responsiveness with CSS. Learning tip: Let CSS do the calculation and not style with JS. After that, I had some merge problems with the "main" branch, but luckily Tristan could help me out. In hindsight, it wasn't necessary, because I had done it right but overlooked something.</p>

<h3>27/03/2024</h3>
<p>On Wednesday, I was busy with some minor tweaks to the "top part" of the slot machine and making my own icons for the slot machine. In the afternoon, I helped Bart animate the CSS Day Logo. Each time you spin the slot machine, we want the color that corresponds to that year. And then I helped Ali transfer his layout of the "lower part" to his own branch.</p>
<img width="700" src="https://github.com/AliAhmed205/hackathon2324/assets/118130116/acbe8671-eece-49cf-96ed-71c925416575">

<h3>Challenges</h3>
<p>Today actually went quite well, we merged all the work together at the end of the day which did cause some merge conflicts but we resolved them and now it works as intended.</p>

<h3>28/03/2024</h3>
<p>On Thursday, it was mainly about dotting the i's and crossing the t's. I was first busy making some minor adjustments to the layout and then made sure that when you pull the lever down, it automatically goes to the lower part. Then I merged my part with Ali's.</p>

<h2>Bart</h2>

<h3>25/03/2024</h3>
<p>I was tasked with fetching the data and sorting it by year and countries.</p>

<p>What I did</p>
<p>All data loading</p>

<p>I did a fetch via JavaScript to load all the data from the external JSON file. This was successful.</p>
<pre>
fetch('https://cssday.nl/data/speakers.json')
    .then(response => response.json())
    .then(data => {
        allData = data
    })
    .catch(error => {
        console.error('Error fetching data:', error)
    })
</pre>
<p>Selecting a year based on country or year</p>
<p>I can filter all data by year or country</p>
<pre>
<label for="year-select">Filter by Year:</label>
<select id="year-select">
  <option value="">Everything</option>
  <option value="2013">2013</option>
  <option value="2014">2014</option>
  <option value="2015">2015</option>
  <option value="2016">2016</option>
  <option value="2017">2017</option>
  <option value="2018">2018</option>
  <option value="2019">2019</option>
  <option value="2022">2022</option>
  <option value="2023">2023</option>
  <option value="2024">2024</option>
</select>
</pre>

<h3>26/03/2024</h3>
<p>My goal for today is that I only want to see the countries of the selected year. I also want to dynamically load the list of characters with only certain data</p>
<p>Making a list of people (ul)</p>
<p>Person comes in an (li)</p>
<p>Name (h2)</p>
<p>const speakerYear = document.createElement("h1");</p>
<p>Photo (img)</p>
<p>Title (h3)</p>
<p>Description (p)</p>
<pre>
const speakersList = document.createElement('ul');
data.forEach(speaker => {
    const speakerItem = document.createElement('li');
    let speakerDetails = speaker.name;
    if (speaker.talk && speaker.talk.title) { // Adjusted to access the title property
        speakerDetails += ` - "${speaker.talk.title}"`; // Using the title
    }
    // If there are other properties you wish to display, access them similarly
    speakerItem.textContent = speakerDetails;
    speakersList.appendChild(speakerItem);
});
</pre>

<h3>27/03/2024</h3>
<p>Changing SVG color upon click by the color of the year</p>
<pre>
document.getElementById('year-select').addEventListener('change', () => {
    const selectedYear = document.getElementById('year-select').value;
    const fill = yearColors[selectedYear];
    document.querySelectorAll('svg').forEach(svg => {
        svg.style.fill = fill;
    });

});

</pre>
<p>On a new click, the color goes away and then comes back with a box shadow</p>
<pre>
svgAnimation.forEach(path => {
    path.classList.remove('new-color')
});

setTimeout(() => {
document.documentElement.style.setProperty('--svg-color', colours[randomYear.index]);

    svgAnimation.forEach(path => {
        path.classList.add('new-color');

    });

}, 1000);

</pre>

<h3>28/03/2024</h3>
<p>Merging</p>
<p>At the end of the day, we merged the codes of all four of us.</p>
