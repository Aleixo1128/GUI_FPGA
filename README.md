# GUI_FPGA

GUI for the DE10-Standard (Cyclone V SoC 5CSXFC6D6F31C6N) with MTL2 800x480 touchscreen,
controlling the VHDL sine signal generator in the FPGA.

## Folders
- `fpga/`          Quartus project, Platform Designer system, VHDL
- `hps/`           Linux application: LVGL port, drivers, register access
- `SquareLine UI/` SquareLine project (GUI_FPGA.spj) and exported UI code
- `docs/`          Manuals and wiring notes

## Workflow
- Never commit directly to `main`. Create a branch and open a pull request.
- Open `SquareLine UI/GUI_FPGA.spj` in SquareLine to edit the screen.
- Only edit code between `USER CODE BEGIN` and `USER CODE END` in exported files.
