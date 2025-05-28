# SOC
RISC based SOC design 
<br>
check out the documentation section
To ensure the SoC project directory structure is formatted for direct pasting into a GitHub README, it needs to be enclosed in a Markdown code block using triple backticks (```) with no language specifier, as this preserves the exact formatting and special characters (like └── and ├──) used in the tree structure. Below is the exact content you can copy and paste into your GitHub README.md file.

```
```
SoC_Project/
├── docs/                     # Design docs, architecture specs, memory maps
├── arch/
│   ├── diagrams/             # Block diagrams, timing diagrams
│   └── specs/                # ISA selection, memory map, interconnect plan
├── modeling/
│   ├── qemu/                 # QEMU pre-RTL simulation platform
│   └── systemc/              # SystemC TLM modeling of the SoC
├── rtl/
│   ├── core/                 # RISC-V core integration (Rocket/CVA6)
│   ├── interconnect/         # AXI buses, arbiters
│   ├── peripherals/          # UART, Timer, SPI, GPIO, PLIC
│   ├── fpga_ctrl/            # AXI-Lite to FPGA bridge + config/status
│   └── top/                  # SoC top-level wrapper
├── tb/
│   ├── verilator/            # Verilator C++ testbenches
│   └── cocotb/               # Python-based testbenches
├── software/
│   ├── bootloader/           # FSBL/U-Boot source
│   ├── kernel/               # Linux kernel source/configs
│   └── rootfs/               # Buildroot or Yocto setup
├── fpga_bitstreams/         # FPGA accelerator bitstream binaries
├── device_tree/             # DTS and DTB files
├── scripts/                 # Helper scripts for simulation, flashing, etc.
├── Makefile                 # Top-level build manager
└── README.md
```
```

