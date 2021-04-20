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

Please enter the composition of your team (for Project 3-5) by
filling this <a href="https://forms.gle/DwNN1pZPn5J6jFAS9">Google Form</a>. 
Each team can have at most 2 people, and 2) if you choose to work as
a team, only one team member needs to fill this form.

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
     <b>Reading:</b> <a href="http://pages.cs.wisc.edu/~remzi/OSTEP//intro.pdf">Intro</a> and
         <a href="http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-intro.pdf">Process</a> and
         <a href="http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-api.pdf">Process API</a><br/>
	<span class="assignment"><a href="./proj0a.html">Proj 0a</a> and 
		<a href="./proj0b.html">Proj 0b</a> out</span></td>
  <td class="nodue">Jan 29</td>
</tr>
<tr> <!-- week of Feb 3 -->
  <td id="2021-2-3" class="date"><b>Week 2</b></td>
  <td class="virtualization">Feb 3<br/>
	<b>Lec 2a:</b> LDE [<a href="./public/lecs/lec2a-lde.pdf">slides</a>]<br/>
	<b>Lec 2b:</b> CPU virtualization I [<a href="./public/lecs/lec2b-sched-fifo-sjf-rr.pdf">slides</a>]<br/>
	Lec 2's note [<a href="./public/lecs/Lec2.pdf">note</a>]<br/>
	<b>Reading:</b> <a href="http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-mechanisms.pdf">LDE</a> and <a href="http://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/cpu-sched.pdf">Scheduling (intro)</a>
	</td>
  <td class="deadline">Feb 5<br/>
	<span class="hwdue"><a href="./proj0a.html">Proj 0a</a> due</span><br/>
	<span class="assignment"><a href="./proj1.html">Proj 1</a> out</span></td>
</tr>
<tr> <!-- week of Feb 10 -->
  <td id="2021-2-10" class="date"><b>Week 3</b></td>
  <td class="virtualization">Feb 10<br/>
	<b>Lec 3:</b> CPU virtualization II [<a href="./public/lecs/lec3-sched-priority-mlfq-cfs.pdf">slides</a>]<br/>
	Lec 3's note [<a href="./public/lecs/Lec3.pdf">note</a>]<br/>
	<b>Reading:</b> <a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/cpu-sched-mlfq.pdf">MLFQ</a>, <a href="https://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-multi.pdf">Multi-core Sched (Linux)</a>, <a href="https://man7.org/linux/man-pages/man7/sched.7.html">man 7 sched</a>, and <a href="https://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-lottery.pdf">Lottery (optional)</a>
	</td>
  <td class="nodue">Feb 12</td>
</tr>
<tr> <!-- week of Feb 17 -->
  <td id="2021-2-17" class="date"><b>Week 4</b></td>
  <td class="virtualization">Feb 17<br/>
	<b>Lec 4:</b> Memeory virtualization I [<a href="./public/lecs/lec4-vm-paging.pdf">slides</a>]<br/>
	Lec 4's note [<a href="./public/lecs/Lec4.pdf">note</a>]<br/>
	<b>Reading:</b> <a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/vm-intro.pdf">Address spaces</a>, <a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/vm-mechanism.pdf">Address translation</a>, 
	<a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/vm-paging.pdf">Paging</a>, 
	<a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/vm-tlbs.pdf">TLB</a>, 
	and <a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/vm-smalltables.pdf">Adv. PTs</a> 
	</td>
  <td class="nodue">Feb 19</td>
</tr>
<tr> <!-- week of Feb 24 -->
  <td id="2021-2-24" class="date"><b>Week 5</b></td>
  <td class="virtualization">Feb 24<br/>
	<b>Lec 5:</b> Memory virtualization II [<a href="./public/lecs/lec5-vm-caching.pdf">slides</a>]<br/>
	Lec 5's note [<a href="./public/lecs/Lec5.pdf">note</a>]<br/>
	<b>Reading:</b> Beyond physical memory: <a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/vm-beyondphys.pdf">Mechanisms</a>, 
	<a href="https://pages.cs.wisc.edu/~remzi/OSTEP/vm-beyondphys-policy.pdf">(Caching) Policy</a>, 
	and <a href="https://www.usenix.org/conference/fast-03/arc-self-tuning-low-overhead-replacement-cache">ARC paper (FAST'03)</a>
	</td>
  <td class="deadline">Feb 26<br/>
	<span class="hwdue"><a href="./proj1.html">Proj 1</a> due</span><br/>
	<span class="assignment"><a href="./proj2.html">Proj 2</a> out</span></td>
</tr>
<tr> <!-- week of Mar 2 -->
  <td id="2021-3-3" class="date"><b>Week 6</b></td>
  <td class="lecture">Mar 3<br/>
	<b>Lec 6:</b> Midterm review  [<a href="./public/lecs/midterm-review.pdf">slides</a>] [<a href="./public/lecs/midterm-review+notes.pdf">slides+notes</a>] </td>
  <td class="nodue">Mar 5</td>
</tr>
<tr> <!-- week of Mar 9 -->
  <td id="2021-3-10" class="date"><b>Week 7</b></td>
  <td class="exam">Mar 10<br/>
	<b>Midterm exam</b></td>
  <td class="nodue">Mar 12<br/>
	<a href="./midterm_stats.html">Midterm stats</a>
	</td>
</tr>
<tr> <!-- week of Mar 16 -->
  <td id="2021-3-17" class="date"><b>Week 8</b></td>
  <td class="concurrency">Mar 17<br/>
	<b>Lec 7:</b> Concurrency I [<a href="./public/lecs/lec7-concur-threads-locks-sem.pdf">slides</a>]<br/>
	Lec 7's note [<a href="./public/lecs/Lec7.pdf">note</a>]<br/>
	<b>Reading:</b> <a href="https://pages.cs.wisc.edu/~remzi/OSTEP/threads-api.pdf">Threads</a>, 
	<a href="https://pages.cs.wisc.edu/~remzi/OSTEP/threads-intro.pdf">Concurrency intro</a>,
	<a href="https://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks.pdf">Locks</a>, and
	<a href="https://pages.cs.wisc.edu/~remzi/OSTEP/threads-sema.pdf">Semaphores</a>
	</td>
  <td class="nodue">Mar 19<br/>
	<span class="hwdue"><s><a href="./proj2.html">Proj 2</a> due</s></span><br/>
	<span class="assignment"><del><a href="./proj3.html">Proj 3</a> out</del></span></td>
</tr>
<tr> <!-- week of Mar 23 -->
  <td id="2021-3-24" class="date"><b>Week 9</b></td>
  <td class="concurrency">Mar 24<br/>
	<b>Lec 8:</b> Concurrency II [<a href="./public/lecs/lec8-concur-cv-pcp-5dp.pdf">slides</a>] <br/>
	Lec 8's note [<a href="./public/lecs/Lec8.png">note</a>]<br/>
	<b>Reading:</b> <a href="https://pages.cs.wisc.edu/~remzi/OSTEP/threads-cv.pdf">CV</a>, <a href="https://pages.cs.wisc.edu/~remzi/OSTEP/threads-bugs.pdf">Deadlocks</a>
	</td>
  <td class="deadline">Mar 26<br/>
	<span class="hwdue"><a href="./proj2.html">Proj 2</a> due</span><br/>
	<span class="assignment"><a href="./proj3.html">Proj 3</a> out</span></td>
</tr>
<tr> <!-- week of Mar 30 -->
  <td id="2021-3-31" class="date"><b>Week 10</b></td>
  <td class="persistence">Mar 31<br/>
	<b>Lec 9:</b> Persistence I [<a href="./public/lecs/lec9-persis-hdd-ssd.pptx">slides</a>] <br/>
	Lec 9's note [<a href="./public/lecs/Lec9.png">note</a>]<br/>
	<b>Reading:</b> <a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/file-disks.pdf">HDDs</a>, 
	<a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/file-disks.pdf">Disk sched</a>, and
	<a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/file-ssd.pdf">SSDs</a> 
	</td>
  <td class="lecture">Apr 2<br/>
	<b>Go basics:</b> Go tutorial [<a href="https://drive.google.com/file/d/1RgAvty5D5BGJLiilIqVppIY2FBpZ2q6N/view?usp=sharing">video</a>] <br/>
	[<a href="./public/lecs/go_basics.pdf">slides</a>] [<a href="./public/lecs/go_handout.docx">handout1</a>] [<a href="./public/lecs/go_handout2.docx">handout2</a>]
	</td>
</tr>
<tr> <!-- week of Apr 6 -->
  <td id="2021-4-7" class="date"><b>Week 11</b></td>
  <td class="persistence">Apr 7<br/>
	<b>Lec 10:</b> Persistence II [<a href="./public/lecs/lec10-persis-fs-raid.pdf">slides</a>] [<a href="./public/lecs/lec10-persis-fs-raid+note.pdf">slides+notes</a>] <br/>
	<b>Reading:</b> <a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/file-intro.pdf">File system intro</a>, 
	<a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/file-implementation.pdf">file system implementation</a>, and
	<a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/file-raid.pdf">RAID</a>
	</td>
  <td class="deadline">Apr 9<br/>
	<span class="hwdue"><a href="./proj0b.html">Proj 0b</a> due </span></td>
</tr>
<tr> <!-- week of Apr 13 -->
  <td id="2021-4-14" class="date"><b>Week 12</b></td>
  <td class="advanced">Apr 14<br/>
	<b>Lec 11:</b> Distributed systems I: RPC, MapReduce [<a href="./public/lecs/lec11-ds-rpc-mr.pdf">slides</a>] <br/>
	<b>Reading:</b> <a href="./public/lecs/mapreduce_osdi04.pdf">MapReduce paper</a>
	</td>
  <td class="deadline">Apr 16<br/>
	<span class="hwdue"><a href="./proj3.html">Proj 3</a> due</span><br/>
	<span class="assignment"><a href="./proj4.html">Proj 4</a> out</span></td>
</tr>
<tr> <!-- week of Apr 20 -->
  <td id="2021-4-21" class="date"><b>Week 13</b></td>
  <td class="advanced">Apr 21<br/>
	<b>Lec 12:</b> Distributed systems II: GFS, NFS [<a href="./public/lecs/lec12-ds-gfs-nfs.pdf">slides</a>] <br/>
	<b>Reading:</b> <a href="./public/lecs/gfs_sosp03.pdf">GFS paper</a>
	</td>
  <td class="important">Apr 23<br/>
	<span class="assignment"><a href="./proj5.html">Proj 5</a> out</span></td>
</tr>
<tr> <!-- week of Apr 27 -->
  <td id="2021-4-28" class="date"><b>Week 14</b></td>
  <td class="lecture">Apr 28<br/>
	<b>Final review</b>  </td>
  <td class="nodue">Apr 30</td>
</tr>
<tr> <!-- week of May 4 -->
  <td id="2021-5-5" class="date"><b>Week 15</b></td>
  <td class="exam">May 5<br/>
	 <b>Final exam</b> 7:20 pm - 10:00 pm</td>
  <td class="deadline">May 7<br/>
	<span class="hwdue"><a href="./proj4.html">Proj 4</a> due</span></td>
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
