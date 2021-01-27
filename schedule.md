---
layout: page
title: "Course Schedule"
permalink: /schedule.html
---

<style>
table.calendar {
    font-family: arial, helvetica;
    font-size: 10pt;
    empty-cells: show;
    border: 1px solid #000000;
    border-collapse: collapse;
}
table.calendar tr td {
    border: 1px solid #aaaaaa;
}
table.calendar tr {
    vertical-align: top;
    height: 5em;
    background: #ffffff;
}
table.calendar thead tr {
    text-align: center;
    background: #444444;
    color: #ffffff;
    height: auto;
    font-weight: bold;
}
/*.date {
	background: Gainsboro;
}*/
.holiday {
    background: #F0FFF0;
}
.lecture {
    background: #ffffaa;
}
.virtualization {
    background: Moccasin;
}
/*.concurrency {
    background: LightGreen;
}*/
.concurrency {
    background: MediumSpringGreen;
}
.persistence {
    background: Plum;
}
.advanced {
    background: Aqua;
}
.presentation {
    background: Plum;
}
.exam {
    background: DarkOrange;
}
.important {
    background: Bisque;
}
.nodue {
    background: #FFFAFA;
}
.optional {
    background: Linen;
}
.reading {
    color: Black;
}
.deadline {
    background: #ffaaaa;
}
.hwdue {
    color: #ff0000;
	font-weight: bold;
}
.assignment {
    color: #0aa00a;
	font-weight: bold;
}
.date {
	background: #eeeeee;
    color: #444444;
}
</style>

The course schedule is tentative and subject to change\*.

<p>
<table class="calendar" cellspacing="0" cellpadding="6" width="100%">
 <thead>
  <tr>
   <td width="10%">Week</td><td width="60%">Wednesday</td>
   <td width="30%">Friday</td>
  </tr>
 </thead>

<!--tr--> <!-- week of Jan 20 -->
  <!--td id="2020-1-20" class="date"><b>Week 1</b></td>
  <td class="holiday">Jan 27<br/>
	<b>MLK Day</b> (NO CLASS)</td>
  <td class="nodue">Jan 23</td>
</tr-->
<tr> <!-- week of Jan 27 -->
  <td id="2021-1-27" class="date"><b>Week 1</b></td>
  <td class="lecture">Jan 27<br/>
	<b>Lec 1:</b> Introduction, process abstraction [<a href="./public/lecs/lec1-intro.pdf">slides</a>] <br/>
	<span class="assignment"><a href="./proj0a.html">Proj 0a</a> and 
		<a href="./proj0b.html">Proj 0b</a> out</span></td>
  <td class="nodue">Jan 29</td>
</tr>
<tr> <!-- week of Feb 3 -->
  <td id="2021-2-3" class="date"><b>Week 2</b></td>
  <td class="virtualization">Feb 3<br/>
	<b>Lec 2:</b> CPU scheduling I
	</td>
  <td class="deadline">Feb 5<br/>
	<span class="hwdue"><a href="./proj0a.html">Proj 0a</a> due</span><br/>
	<span class="assignment"><a href="./proj1.html">Proj 1</a> out</span></td>
</tr>
<tr> <!-- week of Feb 10 -->
  <td id="2021-2-10" class="date"><b>Week 3</b></td>
  <td class="virtualization">Feb 10<br/>
	<b>Lec 3:</b> CPU scheduling II	</td>
  <td class="nodue">Feb 12</td>
</tr>
<tr> <!-- week of Feb 17 -->
  <td id="2021-2-17" class="date"><b>Week 4</b></td>
  <td class="virtualization">Feb 17<br/>
	<b>Lec 4:</b> Memeory management I</td>
  <td class="nodue">Feb 19</td>
</tr>
<tr> <!-- week of Feb 24 -->
  <td id="2021-2-24" class="date"><b>Week 5</b></td>
  <td class="virtualization">Feb 24<br/>
	<b>Lec 5:</b> Memory management II
	</td>
  <td class="deadline">Feb 26<br/>
	<span class="hwdue"><a href="./proj1.html">Proj 1</a> due</span><br/>
	<span class="assignment"><a href="./proj2.html">Proj 2</a> out</span></td>
</tr>
<tr> <!-- week of Mar 2 -->
  <td id="2021-3-3" class="date"><b>Week 6</b></td>
  <td class="concurrency">Mar 3<br/>
	<b>Lec 6:</b> Thread <br/>
	<b>Midterm review</b> </td>
  <td class="nodue">Mar 5</td>
</tr>
<tr> <!-- week of Mar 9 -->
  <td id="2021-3-10" class="date"><b>Week 7</b></td>
  <td class="exam">Mar 9<br/>
	<b>Midterm exam</b> </td>
  <td class="nodue">Mar 12</td>
</tr>
<tr> <!-- week of Mar 16 -->
  <td id="2021-3-17" class="date"><b>Week 8</b></td>
  <td class="concurrency">Mar 17<br/>
	<b>Lec 7:</b> Concurrency I </td>
  <td class="deadline">Mar 19<br/>
	<span class="hwdue"><a href="./proj2.html">Proj 2</a> due</span><br/>
	<span class="assignment"><a href="./proj3.html">Proj 3</a> out</span></td>
</tr>
<tr> <!-- week of Mar 23 -->
  <td id="2021-3-24" class="date"><b>Week 9</b></td>
  <td class="concurrency">Mar 24<br/>
	<b>Lec 8:</b> Concurrency II </td>
  <td class="nodue">Mar 26</td>
</tr>
<tr> <!-- week of Mar 30 -->
  <td id="2021-3-31" class="date"><b>Week 10</b></td>
  <td class="persistence">Mar 31<br/>
	<b>Lec 9:</b> I/O, disks  </td>
  <td class="nodue">Apr 2</td>
</tr>
<tr> <!-- week of Apr 6 -->
  <td id="2021-4-7" class="date"><b>Week 11</b></td>
  <td class="advanced">Apr 7<br/>
	<b>Lec 10:</b> Distributed systems I: RPC, MapReduce 
	</td>
  <td class="deadline">Apr 9<br/>
	<span class="hwdue"><a href="./proj0b.html">Proj 0b</a> and 
		<a href="./proj3.html">Proj 3</a> due</span><br/>
	<span class="assignment"><a href="./proj4.html">Proj 4</a> out</span></td>
</tr>
<tr> <!-- week of Apr 13 -->
  <td id="2021-4-14" class="date"><b>Week 12</b></td>
  <td class="persistence">Apr 14<br/>
	<b>Lec 11:</b> File systems
	</td>
  <td class="nodue">Apr 16</td>
</tr>
<tr> <!-- week of Apr 20 -->
  <td id="2021-4-21" class="date"><b>Week 13</b></td>
  <td class="advanced">Apr 21<br/>
	<b>Lec 12:</b> Distributed systems II: GFS, NFS</td>
  <td class="important">Apr 23<br/>
	<span class="assignment"><a href="./proj5.html">Proj 5</a> out</span></td>
</tr>
<tr> <!-- week of Apr 27 -->
  <td id="2021-4-28" class="date"><b>Week 14</b></td>
  <td class="lecture">Apr 28<br/>
	<b>Final review</b>  </td>
  <td class="deadline">Apr 30<br/>
	<span class="hwdue"><a href="./proj4.html">Proj 4</a> due</span></td>
</tr>
<tr> <!-- week of May 4 -->
  <td id="2021-5-5" class="date"><b>Week 15</b></td>
  <td class="exam">May 5<br/>
	 <b>Final exam</b> 7:20 pm - 10:00 pm</td>
  <td class="nodue">May 7</td>
</tr>

</table>

</p>

<p style='font-size:12pt'>&#42;: Color codings:
<table style='font-size:12pt'>
<tr> 
	<td class="virtualization"> -Virtualization- </td>
	<td class="concurrency"> -Concurrency- </td>
	<td class="persistence"> -Persistence- </td>
	<td class="advanced"> -Distributed Systems- </td>
</tr>
</table>
