.. highlight:: rst

Projects
=====================================

.. raw:: html

   <hr>

`Amandroid <http://www.arguslab.org/android.html>`_
------------------------------------

The Android smart-phone platform is very popular. Recently, malicious or vulnerable applications have been reported to cause several security problems. However, there is no effective method that a market operator can use to vet apps entering a market (e.g. Google Play). 
Prior works using static analysis to address Android app security problems more focus on specific problems and built specialized tools for them. We observe that a large portion of those security issues can be resolved by addressing one underlying core problem – capturing semantic behaviors of the app such as object points-to and control-/data-flow information. Thus, we designed a new approach to conducting static analysis for vetting Android apps, and built a generic framework, called Amandroid, which does flow and context-sensitive data flow analysis in an inter-component way. 
Our approach shows that a comprehensive static analysis method on Android apps is totally feasible in terms of compotation resources, and Amandroid framework is flexible and easy to be extended for many types of specialized security analyses.
Since Amandroid directly handles Inter-component control and data flows, it can be used to address security problems that results from interactions among multiple components from either the same or different apps. Amandroid analysis is sound in that it can provide assurance of the absence of the specified security problems in an app with well-specified and reasonable assumptions on the Android runtime and its library.
On top of Amandroid framework we performed certain specific security analyses, for instance, a) user password flow tracking, b) intent injection detection, c) crypto API misuse checking. We apply those analyses on 450 apps collected from Google Play’s popular apps and a third-party security company, and the results show that it is capable of finding real security issues and efficient enough in terms of analysis time.Amandroid 0.2: `mac64 <http://people.cis.ksu.edu/~fgwei/resources/AmandroidCli-mac64.zip>`_

.. raw:: html

   <hr>
   <br/>
   <br/>
   <br/>
   <br/>
   <br/>
   <br/>
   <br/>
   <br/>
   