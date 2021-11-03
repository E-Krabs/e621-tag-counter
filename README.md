# e621-json-dump
Scripts to analyze the furry fandom through the content it produces.
<hr>
<ul>
  <li><code>main.py</code> Dumps https://e621.net/posts.json. Dumps as much as it can (~950,000/~2.5mil Posts). Takes ~6 hours to complete.<br>
  <li><code>tag_popularity.py</code> Plots the popularity of two tags to compare (from 2007-2021).<br>
  <li><b>Merge</b><code>tag_export.py</code> Exports tag data from the huge JSON file to a smaller file for easier interpretation.<br>
  <li><b>Merge</b><code>tag_count.py</code> Counts tag data from the exported JSON file. (Artist, General, Species, Characters, etc.)<br>
  <li><b>Merge</b><code>id_export.py</code> Exports all post ids from the huge JSON file to a smaller file for easier interpretation.<br>
  <li><b>Merge</b><code>id_count.py</code> Counts all ids from the exported JSON file. Gives total number of posts.<br>

<h3><b>TODO:<b></h3><br>
<ul>
  <li><b>Extract</b> <code>created_at</code> and <code>tags</code> to plot popularity of a tag over a time period.</li>
  <b>[+++++++++_] 90%</b><br>
  <li><b>Merge</b> <code>tag_export.py</code> and <code>tag_count.py</code></li>
  <b>[++________] 20%</b>
 </ul>
