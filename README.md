# Cadence NatureDSP Library for MathX 110 DSP cores

<p>This NatureDSP Library for MathX 110 DSP contains various optimized general purpose signal processing routines.</p>

<h1> Version: v3.0.0 </h1>
       <p>This is an early access (v3.0.0) of NatureDSP library for MathX 110 DSP.
This version of library has been tested with RJ-2024.3 Xtensa tools 
and has all the APIs with its predecessor, FloatingPoint KP1.

This release contains following changes when compared to the previous release of FloatingPoint KP1 library v2.1.0:
      </p>
 <h3> Changes:</h3>
       <p>
       <ol>
      <li>single precision floating point additional APIs: erf, cmatmulmxnxps, matmulmxnxps, streaming Chol and QR</li>
	  <li>xt-clang LLVM15 migration related changes and fixes</li>
      </ol>
      </p>
<h3> Known issues:</h3>
     <p>
     <ol>
    <li>Performance of some functions may need further tuning for RJ-2024.3 tools</li>
     </ol>
     </p>
<h1> Version: v2.1.0 </h1>
 <h3> Details:</h3>
       <p>
       <ol>
      <li>This version of library has been optimized and tested with RI-2022.9 Xtensa tools.</li>
      </ol>
      </p>
<h3> Known issues:</h3>
     <p>
     <ol>
    <li> None</li>
     </ol>
     </p>



<h1>To use the library </h1>
<p>
<ol>
<li>Download the library & demo xws from the repository and import them into Xtensa Xplorer environment.</li>
<li>Upon importing, two directories i.e. mathx110_library & mathx110_demo  will be available in the Project Xplorer pane.</li>
<li>Refer to Chapter-3 of "NatureDSP_Library_Reference_MathX_110.pdf" document present inside the mathx110_library/doc directory for details on build and run.</li>
<li>Detailed Release notes can be found at mathx110_library/doc directory.</li>
</ol>
</p>

