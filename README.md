# SOC
RISC based SOC design 
<br>
check out the documentation section
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
