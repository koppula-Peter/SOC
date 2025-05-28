# SOC
RISC based SOC design 
<br>
check out the documentation section
formatTreeString(
  {
    text: 'SoC_Project',
    children: [
      {
        text: 'docs',
        extra: 'Design docs, architecture specs, memory maps'
      },
      {
        text: 'arch',
        children: [
          {
            text: 'diagrams',
            extra: 'Block diagrams, timing diagrams'
          },
          {
            text: 'specs',
            extra: 'ISA selection, memory map, interconnect plan'
          }
        ]
      },
      {
        text: 'modeling',
        children: [
          {
            text: 'qemu',
            extra: 'QEMU pre-RTL simulation platform'
          },
          {
            text: 'systemc',
            extra: 'SystemC TLM modeling of the SoC'
          }
        ]
      },
      {
        text: 'rtl',
        children: [
          {
            text: 'core',
            extra: 'RISC-V core integration (Rocket/CVA6)'
          },
          {
            text: 'interconnect',
            extra: 'AXI buses, arbiters'
          },
          {
            text: 'peripherals',
            extra: 'UART, Timer, SPI, GPIO, PLIC'
          },
          {
            text: 'fpga_ctrl',
            extra: 'AXI-Lite to FPGA bridge + config/status'
          },
          {
            text: 'top',
            extra: 'SoC top-level wrapper'
          }
        ]
      },
      {
        text: 'tb',
        children: [
          {
            text: 'verilator',
            extra: 'Verilator C++ testbenches'
          },
          {
            text: 'cocotb',
            extra: 'Python-based testbenches'
          }
        ]
      },
      {
        text: 'software',
        children: [
          {
            text: 'bootloader',
            extra: 'FSBL/U-Boot source'
          },
          {
            text: 'kernel',
            extra: 'Linux kernel source/configs'
          },
          {
            text: 'rootfs',
            extra: 'Buildroot or Yocto setup'
          }
        ]
      },
      {
        text: 'fpga_bitstreams',
        extra: 'FPGA accelerator bitstream binaries'
      },
      {
        text: 'device_tree',
        extra: 'DTS and DTB files'
      },
      {
        text: 'scripts',
        extra: 'Helper scripts for simulation, flashing, etc.'
      },
      {
        text: 'Makefile',
        extra: 'Top-level build manager'
      },
      {
        text: 'README.md'
      }
    ]
  },
  {
    guideFormat: chalk.dim
  }
);
