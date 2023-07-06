# Awesome Hardware Description Languages

A curated list of amazingly awesome hardware description language projects.


# Hardware development

## HDL doc

* Verilog [IEEE Std 1364-2001](https://inst.eecs.berkeley.edu/~cs150/fa06/Labs/verilog-ieee.pdf), [Quick Ref Guide](http://sutherland-hdl.com/pdfs/verilog_2001_ref_guide.pdf), [SystemVerilog 3.1a](http://www.ece.uah.edu/~gaede/cpe526/SystemVerilog_3.1a.pdf), [Synthesizing SystemVerilog Busting the Myth that SystemVerilog is only for Verification](http://sutherland-hdl.com/papers/2013-SNUG-SV_Synthesizable-SystemVerilog_paper.pdf)
* VHDL standards [IEEE Std 1076-2000](http://edg.uchicago.edu/~tang/VHDLref.pdf)
* SystemC standards [IEEE Std 1666-2011](http://paginas.fe.up.pt/~ee07166/lib/exe/fetch.php?media=1666-2011.pdf)


## HDL simulators and compilers

   * Verilog
      - [Verilator](https://www.veripool.org/wiki/verilator) Verilog to C++ transpiler
      - [Icarus Verilog](http://iverilog.icarus.com/) - simulator
      - [Yosys](http://www.clifford.at/yosys/) - RTL synthesis
   * VHDL
      * [nvc](https://github.com/nickg/nvc) - GPLv3 VHDL compiler and simulator, IEEE 1076-2002, written in C
      * [GHDL](https://github.com/ghdl/ghdl) - VHDL compiler and simulator, IEEE 1076-2002, written in ADA
   * chisel/firrtl
      * [essent](https://github.com/ucsc-vama/essent) - firrtl to optimized C++ transpiler
      * [treadle](https://github.com/chipsalliance/treadle) - firrtl simulator written in Scala
   * [Lola-2](https://inf.ethz.ch/personal/wirth/Lola/Lola2.pdf)
      - [Oberon-2013](https://inf.ethz.ch/personal/wirth/Lola/) - Project Oberon, 2013 Edition, written in [Oberon-07](http://www-oldurls.inf.ethz.ch/personal/wirth/Oberon/) [License](https://inf.ethz.ch/personal/wirth/ProjectOberon/license.txt)


## Meta HDL and Transpilers

* C++
   - [SystemC](https://www.doulos.com/knowhow/systemc/) - an IEEE standard meta-HDL
   - [VisualHDL](http://sysprogs.com/legacy/visualhdl/) - an integrated development environment (IDE) rapid design for FPGAs

* Dart
   - [ROHD](https://github.com/intel/rohd) - A framework for hardware description and verification, 2021+

* Haskell
   - [concat](https://github.com/conal/concat) Haskell to hardware, 2016+
   - https://github.com/conal/talk-2015-haskell-to-hardware
   - [CλaSH](https://github.com/clash-lang/clash-compiler) - A functional hardware description language
   - [pipelineDSL](https://github.com/p12nGH/pipelineDSL) - A Haskell DSL for describing hardware pipelines
   - [Bluespec](https://github.com/B-Lang-org/bsc) - Compiler, simulator, and tools for the Bluespec Hardware Description Language.
   - [sv2v](https://github.com/zachjs/sv2v) - SystemVerilog to Verilog conversion

* Java
   - [jhdl](http://www.jhdl.org/) ..2006
   - [PSHDL](http://pshdl.org/)

* JavaScript
   - [reqack](https://github.com/drom/reqack) -  elastic circuit toolchain
   - [hdl-js](https://github.com/DmitrySoshnikov/hdl-js) - Hardware description language (HDL) parser, and Hardware simulator.
   - [shdl](https://github.com/jcbuisson/shdl) - Simple Hardware Description Language

* Julia
   - [Julia-Verilog](https://github.com/interplanetary-robot/Verilog.jl) - a Verilog-generation DSL for Julia., 2017

* OCaml
   - [Hardcaml](https://github.com/janestreet/hardcaml/blob/master/docs/index.mdx) An OCaml library for designing hardware, complete with testing and simulation tools.

* Kotlin
  - [Verik](https://github.com/frwang96/verik) HDL for design and verification. generates SV. UVM.

* Python
  - [HWT](https://github.com/Nic30/hwt) Meta HDL, verification env. IP-core generator, analysis tools, HDL glue
  - [garnet](https://github.com/StanfordAHA/garnet) Coarse-Grained Reconfigurable Architecture generator based on magma, 2018+
  - [magma](https://github.com/phanrahan/magma/) - Meta HDL, 2017+
  - [migen](https://github.com/m-labs/migen) - Meta HDL, 2011+
  - [MyHDL](https://github.com/myhdl/myhdl) - Process based HDL, verification framework included, 2004+
  - [nMigen](https://github.com/nmigen/nmigen/) - A refreshed Python toolbox for building complex digital hardware, 2018+
  - [Pyrope](https://masc.soe.ucsc.edu/pyrope.html) - Python-like language supporting "fluid pipelines" and "live flow", 2017+
  - [PyRTL](https://github.com/UCSBarchlab/PyRTL) - Meta HDL, simulator suitable for research.
  - [PyMTL](https://github.com/cornell-brg/pymtl) - Process based HDL, verification framework included, 2014+
  - [veriloggen](https://github.com/PyHDI/veriloggen) - Python, Verilog centric meta HDL with HLS like features, 2015-?
  - [Hdl21](https://github.com/dan-fritchman/Hdl21) - Analog HDL in Python

* Ruby
   - [RHDL](https://github.com/philtomson/RHDL)

* Rust
   - [hoodlum](https://github.com/tcr/hoodlum) - Meta HDL, 2016+
   - [kaze](https://github.com/yupferris/kaze) - Meta HDL, 2019+
   - [calyx](https://github.com/cucapra/calyx) - Intermediate Language (IL) for Hardware Accelerator Generators, 2020+

* Scala
   - [chisel](https://github.com/freechipsproject/chisel3) - Meta HDL, 2012+
   - [SpinalHDL](https://github.com/SpinalHDL/SpinalHDL) - Meta HDL 2012+

* C#
   - [Quokka](https://github.com/EvgenyMuryshkin/qusoc) - C# to low-level RTL translator (Verilog, VHDL) and simulation toolkit examples (gates, components, RISC-V, SoC) 

* Veryl
   - [Veryl](https://github.com/dalance/veryl) - An original HDL based on SystemVerilog / Rust syntax, and transplier to SystemVerilog
    
## HLS

* [hlslibs](https://github.com/hlslibs) - ac_math, ac_dsp, ac_types
* [legup](http://legup.eecg.utoronto.ca/) - 2011-2015, LLVM based c->verilog
* [bambu](http://panda.dei.polimi.it/?page_id=31) - 2003-?, GCC based c->verilog
* [augh](http://tima.imag.fr/sls/research-projects/augh/) - c->verilog, DSP support
* https://github.com/utwente-fmt - abstract hls, verification libraries
* [Shang](https://github.com/etherzhhb/Shang) - 2012-2014, LLVM based, c->verilog
* [xronos](https://github.com/endrix/xronos) - 2012, java, simple HLS
* [Potholes](https://github.com/SamuelBayliss/Potholes) - 2012-2014 - polyhedral model preprocessor, Uses Vivado HLS, PET
* [hls_recurse](https://github.com/m8pple/hls_recurse) - 2015-2016 - conversion of recursive fn. for stackless architectures
* [hg_lvl_syn](https://github.com/funningboy/hg_lvl_syn) - 2010, ILP, Force Directed scheduler
* [abc](https://people.eecs.berkeley.edu/~alanmi/abc/) <2008-?, A System for Sequential Synthesis and Verification
* [polyphony](https://github.com/ktok07b6/polyphony) - 2015-2017, simple python to hdl
* [DelayGraph](https://github.com/ni/DelayGraph) - 2016, C#, register assignment algorithms
* [ahaHLS](https://github.com/dillonhuff/ahaHLS) - 2019, An open source high level synthesis (HLS) tool using LLVM
* [combinatorylogic/soc](https://github.com/combinatorylogic/soc) - 2019, An experimental System-on-Chip with a custom compiler toolchain.
* [Quokka](https://github.com/EvgenyMuryshkin/QuokkaEvaluation) - C# to HL RTL translator
* [Vitis](https://github.com/Xilinx/HLS) - LLVM based, made by Xilinx. [user manual](https://www.xilinx.com/support/documentation/sw_manuals/xilinx2020_2/ug1399-vitis-hls.pdf)


## Other HDL languages

* [act](https://github.com/asyncvlsi/act) - asynchronous circuit/compiler tools
* [autopiper](https://github.com/google/autopiper)
* [TL-Verilog](https://makerchip.com) - 2015+, Supports "timing-abstract" and "transaction-level design" methodologies; supported by proprietary and open-source tools


## Hardware Intermediate Representations

* [CIRCT](https://circt.llvm.org) - 2020+, LLVM / MLIR framework "Circuit IR Compilers and Tools"
* [coreir](https://github.com/rdaly525/coreir) - 2016-?, LLVM HW compiler## License
* [lgraph](https://github.com/masc-ucsc/lgraph) - 2017-?, A Multi-Language Synthesis and Simulation IR for Hardware Design
* [firrtl](https://github.com/freechipsproject/firrtl) - 2016-?, Flexible Intermediate Representation for RTL
* [LLHD](https://github.com/fabianschuiki/llhd) - Low Level Hardware Description — A foundation for building hardware design tools
* [SpyDrNet](https://byuccl.github.io/spydrnet/) - 2019+, Framework for parsing and manipulating structural netlists in Python 
* [VLSIR](https://github.com/Vlsir/Vlsir) - IC Interchange Formats, defined in Google Protobuf SDL

## Synthesis tools

* [vtr-verilog-to-routing](https://github.com/verilog-to-routing/vtr-verilog-to-routing)
* [yosys](https://github.com/YosysHQ/yosys) - RTL synthesis framework


## Visualization and Documentation generators

* [bitfield](https://github.com/drom/bitfield) - Javascript bit field diagram renderer
* [d3-wave](https://github.com/Nic30/d3-wave) - Javascript wave graph visualizer for RTL simulations
* [d3-hwschematic](https://github.com/Nic30/d3-hwschematic) - Javascript hierarchical schematic visualizer for HDLs
* [wavedrom](https://github.com/drom/wavedrom) - Javascript wave graph visualizer for documentations and sim.
* [netlistsvg](https://github.com/nturley/netlistsvg) - Javascript schematic visualizer
* [sphinx-hwt](https://github.com/Nic30/sphinx-hwt) - Plugin for sphinx documentation generator which adds schematic into html documentation.
* [Visual Debug](https://redwoodeda.com/viz) - Custom simulation visualization framework, available within the [Makerchip.com](https://makerchip.com) IDE.


## HDL parsers

* [hdlConvertor](https://github.com/Nic30/hdlConvertor) - Fast (System) Verilog/VHDL parser written as C++ extension for Python
* [pyVHDLParser](https://github.com/Paebbels/pyVHDLParser) - VHDL parser written in Python
* [rust_hdl](https://github.com/kraigher/rust_hdl) - VHDL parser and language server written in Rust
* [sv-parser](https://github.com/dalance/sv-parser) -  IEEE 1800-2017 System Verilog Parser written in Rust
* [verible](https://chipsalliance.github.io/verible/) - Verible provides a SystemVerilog parser, style-linter, and formatter.
* [slang](https://github.com/MikePopoloski/slang) - SystemVerilog compiler and language service.
* [pyverilog](https://github.com/PyHDI/Pyverilog) - Python-based Hardware Design Processing Toolkit for Verilog HDL
* [Surelog](https://github.com/chipsalliance/Surelog) - SystemVerilog 2017 Pre-processor, Parser, Elaborator, UHDM Compiler. Provides IEEE Design/TB C/C++ VPI and Python AST API. 

## Other Simulation tools

* [midas](https://github.com/ucb-bar/midas) - FPGA-Accelerated Simulation Framework Automatically Transforming Arbitrary RTL
* [cocotb](https://github.com/potentialventures/cocotb) - A coroutine based co-simulation library for writing VHDL and Verilog testbenches in Python
* [osvvm](https://github.com/OSVVM/OsvvmLibraries) -  A VHDL verification framework, verification utility library, verification component library, and a simulator independent scripting flow

## Other Design Automation tools

* [RgGen](https://github.com/rggen/rggen) - Code generator tool to generate RTL, UVM RAL models and Wiki documents from CSR specifications
* [sv-tests](https://symbiflow.github.io/sv-tests) - Test suite designed to check compliance with the SystemVerilog standard
* [tbengy](https://github.com/prasadp4009/tbengy) - Code generator tool to generate SV/UVM RTL and Testbech as well scripts with support for bitstream generation for Digilent FPGAs
* [HDLGen](https://github.com/WilsonChen003/HDLGen) - Tool for processing of embedded Perl or Python scripts in Verilog source code.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Aliaksei Chapyzhenka](http://drom.io) has waived all copyright and related or neighboring rights to this work.
