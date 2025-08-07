<style>
.about-wrapper{
  display:flex;
  flex-wrap:wrap;        /* stack on phones */
  align-items:flex-start;
  gap:1.2rem;
}
.about-photo{
  max-width:400px;
  border-radius:4px;
}
.about-text{
  flex:1 1 280px;        /* let text take remaining width */
}
@media(max-width:600px){ /* mobile fallback */
  .about-wrapper{flex-direction:column;}
  .about-photo{margin:0 auto;}
}
</style>

<!-- ========= Hero / About ========= -->
<a id="about"></a>
## About Me
_Ph.D. Candidate, LFCS, School of Informatics, University of Edinburgh_

<div class="about-wrapper">
<img class="about-photo" src="/assets/images/mohan.jpg" alt="My Pic"/>

<div class ="about-text" markdown="1">
I am a 4<sup>th</sup> and final year Ph.D. student supervised by [Prof. Richard Mayr](https://homepages.inf.ed.ac.uk/rmayr/) and [Prof. Kousha Etessami](https://homepages.inf.ed.ac.uk/kousha/). My research focuses on turn-based stochastic games and Markov Decision Processes (MDPs), with an emphasis on systems with multiple objectives. I am also interested in exploring connections between Games and Machine Learning, specifically areas such as Reinforcement Learning, understanding Adversarial training/ learning. During my Ph.D., I interned at J.P.Morgan Time Series and Reinforcement Learning (TSRL) team.


Before my time at Edinburgh, I completed my Masters at École Normale Supérieure Paris-Saclay, where I was advised by [Prof. Amaury Pouly](https://www.pouly.fr/) in problems related to continuous Linear Time Invariant systems. Prior to that, I did my undergraduate at IIT Bombay (Major: Computer Science, Minor: Mathematics). My Bachelor thesis advisor was [Prof. S. Akshay](https://www.cse.iitb.ac.in/~akshayss/) with whom I worked on data automata and using graph semantics to solve the emptiness problem. I was also fortunate to have done internships at Purdue University (with [Prof. Roopsha Samanta](https://www.cs.purdue.edu/homes/roopsha/)) and at MPI Saarbrücken (with [Prof. Joël Ouaknine](https://people.mpi-sws.org/~joel/))

</div>
</div>
