This project is under development; the repository and associated site are not represented as functional at this time.<p>

<details>

<summary>Experiment with collapsed sections</summary>

I am considering using markdown to store annotated ngspice scripts extracted from integrated circuit layout. This text could be considered annotation. The text below could be considered details that you may not want to look at every time. Ref: https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-collapsed-sections. For example:

```
	C0 gpio_analog[17] gpio_noesd[17] 3.97f
	**gpio_analog[17] gpio_noesd[17]
	C1 gpio_analog[17] io_oeb[23] 4.49f
	**gpio_analog[17] io_oeb[23]
	C2 gpio_noesd[17] io_in_3v3[24] 3.32f
	**gpio_noesd[17] io_in_3v3[24]
	C3 io_analog[0] io_analog[1] 43.9f
	**io_analog[0] io_analog[1]
	C4 io_analog[0] io_analog[2] 0.323p
	**io_analog[0] io_analog[2]
	C5 io_analog[0] io_analog[4] 4.38f
	**io_analog[0] io_analog[4]
	C6 io_analog[0] io_analog[5] 15.7f
	**io_analog[0] io_analog[5]
	C7 io_analog[0] io_analog[6] 2.51f
	**io_analog[0] io_analog[6]
	C8 io_analog[0] io_analog[8] 16.6f
	**io_analog[0] io_analog[8]
	C9 io_analog[0] vdda2 5.99f
	**io_analog[0] vdda2
	C10 io_analog[0] vssa1 0.273p
	**io_analog[0] vssa1
	C11 io_analog[1] vssa1 35.7f
	**io_analog[1] vssa1
	C12 io_analog[2] io_analog[3] 0.3p
	**io_analog[2] io_analog[3]
	C13 io_analog[2] io_analog[5] 4.38f
	**io_analog[2] io_analog[5]
	C14 io_analog[2] io_analog[6] 16f
	**io_analog[2] io_analog[6]
	C15 io_analog[2] io_analog[7] 2.51f
	**io_analog[2] io_analog[7]
	C16 io_analog[2] vdda2 4.06f
	**io_analog[2] vdda2
	C17 io_analog[2] vssa1 0.103p
	**io_analog[2] vssa1
	C18 io_analog[3] io_analog[4] 0.262p
	**io_analog[3] io_analog[4]
	C19 io_analog[3] io_analog[6] 4.38f
	**io_analog[3] io_analog[6]
	C20 io_analog[3] io_analog[7] 14.4f
	**io_analog[3] io_analog[7]
	C21 io_analog[3] io_analog[8] 4.38f
	**io_analog[3] io_analog[8]
	C22 io_analog[3] vdda2 4.06f
	**io_analog[3] vdda2
	C23 io_analog[3] vssa1 0.103p
	**io_analog[3] vssa1
	C24 io_analog[4] io_analog[5] 0.241p
	**io_analog[4] io_analog[5]
	C25 io_analog[4] io_analog[7] 4.38f
	**io_analog[4] io_analog[7]
	C26 io_analog[4] io_analog[8] 15.8f
	**io_analog[4] io_analog[8]
	C27 io_analog[4] vdda2 5.9f
	**io_analog[4] vdda2
	C28 io_analog[4] vssa1 0.107p
	**io_analog[4] vssa1
	C29 io_analog[5] io_analog[6] 0.269p
	**io_analog[5] io_analog[6]
	C30 io_analog[5] io_analog[8] 2.51f
	**io_analog[5] io_analog[8]
	C31 io_analog[5] vdda2 7.83f
	**io_analog[5] vdda2
	C32 io_analog[5] vssa1 0.11p
	**io_analog[5] vssa1
	C33 io_analog[6] io_analog[7] 0.293p
	**io_analog[6] io_analog[7]
	C34 io_analog[6] vdda2 7.83f
	**io_analog[6] vdda2
	C35 io_analog[6] vssa1 0.117p
	**io_analog[6] vssa1
	C36 io_analog[7] io_analog[8] 0.313p
	**io_analog[7] io_analog[8]
	C37 io_analog[7] vdda2 7.83f
	**io_analog[7] vdda2
	C38 io_analog[7] vssa1 99.7f
	**io_analog[7] vssa1
	C39 io_analog[8] vdda2 0.326p
	**io_analog[8] vdda2
	C40 io_analog[8] vssa1 0.106p
	**io_analog[8] vssa1
	C41 io_analog[9] vssa1 8.53f
	**io_analog[9] vssa1
	C42 io_analog[10] vssa1 22f
	**io_analog[10] vssa1
	C43 io_clamp_high[0] vssa1 2.69f
	**io_clamp_high[0] vssa1
	C44 io_clamp_high[1] vssa1 2.69f
	**io_clamp_high[1] vssa1
	C45 io_clamp_high[2] vssa1 2.83f
	**io_clamp_high[2] vssa1
	C46 io_clamp_low[0] vssa1 2.69f
	**io_clamp_low[0] vssa1
	C47 io_clamp_low[1] vssa1 2.69f
	**io_clamp_low[1] vssa1
	C48 io_clamp_low[2] vssa1 2.83f
	**io_clamp_low[2] vssa1
	C49 io_in[24] io_in_3v3[24] 2.67f
	**io_in[24] io_in_3v3[24]
	C50 io_in[24] io_out[24] 2.01f
	**io_in[24] io_out[24]
	C51 io_in[26] io_out[26] 2.47f
	**io_in[26] io_out[26]
	C52 io_oeb[23] io_out[23] 13.2f
	**io_oeb[23] io_out[23]
	C53 io_oeb[23] vssa1 4.84f
	**io_oeb[23] vssa1
	C54 io_oeb[26] io_out[26] 3.12f
	**io_oeb[26] io_out[26]
	C55 io_oeb[26] vssa1 2.71f
	**io_oeb[26] vssa1
	C56 io_out[23] vssa1 6.83f
	**io_out[23] vssa1
	C57 la_data_out[0] vssa1 57.9f
	**la_data_out[0] vssa1
	C58 la_data_out[1] vssa1 57.9f
	**la_data_out[1] vssa1
	C59 la_data_out[2] la_data_out[3] 30.9f
	**la_data_out[2] la_data_out[3]
	C60 la_data_out[2] note_0/busC 31.7f
	**la_data_out[2] note_0/busC
	C61 la_data_out[2] vssa1 92.6f
	**la_data_out[2] vssa1
	C62 la_data_out[3] la_data_out[4] 30.2f
	**la_data_out[3] la_data_out[4]
	C63 la_data_out[3] vssa1 86.8f
	**la_data_out[3] vssa1
	C64 la_data_out[4] la_data_out[5] 48.3f
	**la_data_out[4] la_data_out[5]
	C65 la_data_out[4] note_0/ip_bar_0[1]/Jx 2.16f
	**la_data_out[4] note_0/ip_bar_0[1]/Jx
	C66 la_data_out[4] vssa1 0.128p
	**la_data_out[4] vssa1
	C67 la_data_out[5] la_data_out[6] 28.7f
	**la_data_out[5] la_data_out[6]
	C68 la_data_out[5] note_0/ip_bar_0[0]/Jx 2.16f
	**la_data_out[5] note_0/ip_bar_0[0]/Jx
	C69 la_data_out[5] note_0/ip_bar_0[2]/Jx 2.16f
	**la_data_out[5] note_0/ip_bar_0[2]/Jx
	C70 la_data_out[5] vssa1 0.131p
	**la_data_out[5] vssa1
	C71 la_data_out[6] la_data_out[7] 27.9f
	**la_data_out[6] la_data_out[7]
	C72 la_data_out[6] vssa1 76.7f
	**la_data_out[6] vssa1
	C73 la_data_out[7] la_data_out[8] 27.2f
	**la_data_out[7] la_data_out[8]
	C74 la_data_out[7] vssa1 76.4f
	**la_data_out[7] vssa1
	C75 la_data_out[8] la_data_out[9] 26.4f
	**la_data_out[8] la_data_out[9]
	C76 la_data_out[8] vssa1 77.6f
	**la_data_out[8] vssa1
	C77 la_data_out[9] vssa1 77.1f
	**la_data_out[9] vssa1
	C78 la_data_out[10] la_data_out[9] 25.7f
	**la_data_out[10] la_data_out[9]
	C79 la_data_out[10] la_data_out[11] 24.9f
	**la_data_out[10] la_data_out[11]
	C80 la_data_out[10] vssa1 76f
	**la_data_out[10] vssa1
	C81 la_data_out[11] la_data_out[12] 24.2f
	**la_data_out[11] la_data_out[12]
	C82 la_data_out[11] vssa1 76.1f
	**la_data_out[11] vssa1
	C83 la_data_out[12] la_data_out[13] 23.4f
	**la_data_out[12] la_data_out[13]
	C84 la_data_out[12] vssa1 71f
	**la_data_out[12] vssa1
	C85 la_data_out[13] la_data_out[14] 22.7f
	**la_data_out[13] la_data_out[14]
	C86 la_data_out[13] vssa1 70.2f
	**la_data_out[13] vssa1
	C87 la_data_out[14] la_data_out[15] 21.9f
	**la_data_out[14] la_data_out[15]
	C88 la_data_out[14] vssa1 69.7f
	**la_data_out[14] vssa1
	C89 la_data_out[15] vssa1 88.8f
	**la_data_out[15] vssa1
	C90 note_0/S0CTc vssa1 2.77f
	**note_0/S0CTc vssa1
	C91 note_0/SOC vssa1 4.47f
	**note_0/SOC vssa1
	C92 note_0/SOT vssa1 2.53f
	**note_0/SOT vssa1
	C93 note_0/busC note_0/busT 32.4f
	**note_0/busC note_0/busT
	C94 note_0/busC vdda2 7.24f
	**note_0/busC vdda2
	C95 note_0/busC vssa1 0.29p
	**note_0/busC vssa1
	C96 note_0/busT vdda2 8.86f
	**note_0/busT vdda2
	C97 note_0/busT vssa1 0.333p
	**note_0/busT vssa1
	C98 note_0/ip_bar_0[0]/Jx note_0/ip_bar_0[0]/Jy 5f
	**note_0/ip_bar_0[0]/Jx note_0/ip_bar_0[0]/Jy
	C99 note_0/ip_bar_0[0]/Jy vdda2 5.42f
	**note_0/ip_bar_0[0]/Jy vdda2
	C100 note_0/ip_bar_0[0]/S0CM vssa1 3.07f
	**note_0/ip_bar_0[0]/S0CM vssa1
	C101 note_0/ip_bar_0[0]/S0TM vssa1 2.83f
	**note_0/ip_bar_0[0]/S0TM vssa1
	C102 note_0/ip_bar_0[0]/ip_cgn_0[0]/Clx vssa1 2.11f
	**note_0/ip_bar_0[0]/ip_cgn_0[0]/Clx vssa1
	C103 note_0/ip_bar_0[0]/ip_cgn_0[1]/Clx vssa1 2.11f
	**note_0/ip_bar_0[0]/ip_cgn_0[1]/Clx vssa1
	C104 note_0/ip_bar_0[0]/ip_cgn_0[2]/Clx vssa1 2.11f
	**note_0/ip_bar_0[0]/ip_cgn_0[2]/Clx vssa1
	C105 note_0/ip_bar_0[0]/ip_cgn_0[3]/Clx vssa1 2.11f
	**note_0/ip_bar_0[0]/ip_cgn_0[3]/Clx vssa1
	C106 note_0/ip_bar_0[0]/ip_cgn_0[4]/Clx vssa1 2.11f
	**note_0/ip_bar_0[0]/ip_cgn_0[4]/Clx vssa1
	C107 note_0/ip_bar_0[0]/ip_clb_0/Bp1C note_0/ip_bar_0[0]/ip_clb_0/Bp1T 7.49f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp1C note_0/ip_bar_0[0]/ip_clb_0/Bp1T
	C108 note_0/ip_bar_0[0]/ip_clb_0/Bp1C note_0/ip_bar_0[0]/ip_clb_0/Bp2C 15.1f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp1C note_0/ip_bar_0[0]/ip_clb_0/Bp2C
	C109 note_0/ip_bar_0[0]/ip_clb_0/Bp1C note_0/ip_bar_0[0]/ip_clb_0/Bp2T 2f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp1C note_0/ip_bar_0[0]/ip_clb_0/Bp2T
	C110 note_0/ip_bar_0[0]/ip_clb_0/Bp1C note_0/ip_bar_0[0]/ip_clb_0/Jx 2.08f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp1C note_0/ip_bar_0[0]/ip_clb_0/Jx
	C111 note_0/ip_bar_0[0]/ip_clb_0/Bp1C note_0/ip_bar_0[0]/ip_clb_0/Jy 2.29f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp1C note_0/ip_bar_0[0]/ip_clb_0/Jy
	C112 note_0/ip_bar_0[0]/ip_clb_0/Bp1C note_0/ip_bar_0[0]/ip_clb_0/p0C 13.6f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp1C note_0/ip_bar_0[0]/ip_clb_0/p0C
	C113 note_0/ip_bar_0[0]/ip_clb_0/Bp1C vdda2 4.14f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp1C vdda2
	C114 note_0/ip_bar_0[0]/ip_clb_0/Bp1C vssa1 9.35f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp1C vssa1
	C115 note_0/ip_bar_0[0]/ip_clb_0/Bp1T note_0/ip_bar_0[0]/ip_clb_0/Bp2T 15.4f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp1T note_0/ip_bar_0[0]/ip_clb_0/Bp2T
	C116 note_0/ip_bar_0[0]/ip_clb_0/Bp1T note_0/ip_bar_0[0]/ip_clb_0/Jx 3.95f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp1T note_0/ip_bar_0[0]/ip_clb_0/Jx
	C117 note_0/ip_bar_0[0]/ip_clb_0/Bp1T note_0/ip_bar_0[0]/ip_clb_0/p0T 13.6f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp1T note_0/ip_bar_0[0]/ip_clb_0/p0T
	C118 note_0/ip_bar_0[0]/ip_clb_0/Bp1T vdda2 3.14f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp1T vdda2
	C119 note_0/ip_bar_0[0]/ip_clb_0/Bp1T vssa1 11.2f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp1T vssa1
	C120 note_0/ip_bar_0[0]/ip_clb_0/Bp2C note_0/ip_bar_0[0]/ip_clb_0/Bp2T 7.49f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp2C note_0/ip_bar_0[0]/ip_clb_0/Bp2T
	C121 note_0/ip_bar_0[0]/ip_clb_0/Bp2C note_0/ip_bar_0[0]/ip_clb_0/Bp3C 15.1f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp2C note_0/ip_bar_0[0]/ip_clb_0/Bp3C
	C122 note_0/ip_bar_0[0]/ip_clb_0/Bp2C note_0/ip_bar_0[0]/ip_clb_0/Bp3T 2f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp2C note_0/ip_bar_0[0]/ip_clb_0/Bp3T
	C123 note_0/ip_bar_0[0]/ip_clb_0/Bp2C note_0/ip_bar_0[0]/ip_clb_0/Jx 2.22f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp2C note_0/ip_bar_0[0]/ip_clb_0/Jx
	C124 note_0/ip_bar_0[0]/ip_clb_0/Bp2C vdda2 4.14f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp2C vdda2
	C125 note_0/ip_bar_0[0]/ip_clb_0/Bp2C vssa1 9.31f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp2C vssa1
	C126 note_0/ip_bar_0[0]/ip_clb_0/Bp2T note_0/ip_bar_0[0]/ip_clb_0/Bp3T 15.4f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp2T note_0/ip_bar_0[0]/ip_clb_0/Bp3T
	C127 note_0/ip_bar_0[0]/ip_clb_0/Bp2T vdda2 3.14f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp2T vdda2
	C128 note_0/ip_bar_0[0]/ip_clb_0/Bp2T vssa1 11.1f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp2T vssa1
	C129 note_0/ip_bar_0[0]/ip_clb_0/Bp3C note_0/ip_bar_0[0]/ip_clb_0/Bp3T 7.49f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp3C note_0/ip_bar_0[0]/ip_clb_0/Bp3T
	C130 note_0/ip_bar_0[0]/ip_clb_0/Bp3C note_0/ip_bar_0[0]/ip_clb_0/Jx 2.16f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp3C note_0/ip_bar_0[0]/ip_clb_0/Jx
	C131 note_0/ip_bar_0[0]/ip_clb_0/Bp3C note_0/ip_bar_0[0]/ip_clb_0/p0C 2f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp3C note_0/ip_bar_0[0]/ip_clb_0/p0C
	C132 note_0/ip_bar_0[0]/ip_clb_0/Bp3C note_0/ip_bar_0[0]/ip_clb_0/p0T 15.1f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp3C note_0/ip_bar_0[0]/ip_clb_0/p0T
	C133 note_0/ip_bar_0[0]/ip_clb_0/Bp3C vdda2 4.14f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp3C vdda2
	C134 note_0/ip_bar_0[0]/ip_clb_0/Bp3C vssa1 9.35f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp3C vssa1
	C135 note_0/ip_bar_0[0]/ip_clb_0/Bp3T note_0/ip_bar_0[0]/ip_clb_0/p0C 15.4f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp3T note_0/ip_bar_0[0]/ip_clb_0/p0C
	C136 note_0/ip_bar_0[0]/ip_clb_0/Bp3T vdda2 3.14f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp3T vdda2
	C137 note_0/ip_bar_0[0]/ip_clb_0/Bp3T vssa1 11f
	**note_0/ip_bar_0[0]/ip_clb_0/Bp3T vssa1
	C138 note_0/ip_bar_0[0]/ip_clb_0/Cl1 vssa1 3.32f
	**note_0/ip_bar_0[0]/ip_clb_0/Cl1 vssa1
	C139 note_0/ip_bar_0[0]/ip_clb_0/Cl2 vssa1 6.03f
	**note_0/ip_bar_0[0]/ip_clb_0/Cl2 vssa1
	C140 note_0/ip_bar_0[0]/ip_clb_0/Jx note_0/ip_bar_0[0]/ip_clb_0/Jy 14.8f
	**note_0/ip_bar_0[0]/ip_clb_0/Jx note_0/ip_bar_0[0]/ip_clb_0/Jy
	C141 note_0/ip_bar_0[0]/ip_clb_0/Jx note_0/ip_bar_0[0]/ip_clb_0/p0C 3.95f
	**note_0/ip_bar_0[0]/ip_clb_0/Jx note_0/ip_bar_0[0]/ip_clb_0/p0C
	C142 note_0/ip_bar_0[0]/ip_clb_0/Jx note_0/ip_bar_0[0]/ip_clb_0/p0T 2.42f
	**note_0/ip_bar_0[0]/ip_clb_0/Jx note_0/ip_bar_0[0]/ip_clb_0/p0T
	C143 note_0/ip_bar_0[0]/ip_clb_0/Jx vssa1 5.51f
	**note_0/ip_bar_0[0]/ip_clb_0/Jx vssa1
	C144 note_0/ip_bar_0[0]/ip_clb_0/Jy note_0/ip_bar_0[0]/ip_clb_0/p0T 2.29f
	**note_0/ip_bar_0[0]/ip_clb_0/Jy note_0/ip_bar_0[0]/ip_clb_0/p0T
	C145 note_0/ip_bar_0[0]/ip_clb_0/Jy vdda2 15.8f
	**note_0/ip_bar_0[0]/ip_clb_0/Jy vdda2
	C146 note_0/ip_bar_0[0]/ip_clb_0/Jy vssa1 3.23f
	**note_0/ip_bar_0[0]/ip_clb_0/Jy vssa1
	C147 note_0/ip_bar_0[0]/ip_clb_0/p0C note_0/ip_bar_0[0]/ip_clb_0/p0T 7.49f
	**note_0/ip_bar_0[0]/ip_clb_0/p0C note_0/ip_bar_0[0]/ip_clb_0/p0T
	C148 note_0/ip_bar_0[0]/ip_clb_0/p0C vdda2 3.14f
	**note_0/ip_bar_0[0]/ip_clb_0/p0C vdda2
	C149 note_0/ip_bar_0[0]/ip_clb_0/p0C vssa1 11f
	**note_0/ip_bar_0[0]/ip_clb_0/p0C vssa1
	C150 note_0/ip_bar_0[0]/ip_clb_0/p0T vdda2 4.14f
	**note_0/ip_bar_0[0]/ip_clb_0/p0T vdda2
	C151 note_0/ip_bar_0[0]/ip_clb_0/p0T vssa1 9.07f
	**note_0/ip_bar_0[0]/ip_clb_0/p0T vssa1
	C152 note_0/ip_bar_0[0]/ip_pbw_0[1]/Cl vssa1 3.31f
	**note_0/ip_bar_0[0]/ip_pbw_0[1]/Cl vssa1
	C153 note_0/ip_bar_0[0]/ip_pbw_0[2]/Cl vssa1 3.31f
	**note_0/ip_bar_0[0]/ip_pbw_0[2]/Cl vssa1
	C154 note_0/ip_bar_0[0]/ip_pbw_0[3]/Cl vssa1 3.32f
	**note_0/ip_bar_0[0]/ip_pbw_0[3]/Cl vssa1
	C155 note_0/ip_bar_0[0]/ip_pbw_0[4]/Cl vssa1 3.32f
	**note_0/ip_bar_0[0]/ip_pbw_0[4]/Cl vssa1
	C156 note_0/ip_bar_0[0]/ip_pbw_0[5]/Cl vssa1 3.32f
	**note_0/ip_bar_0[0]/ip_pbw_0[5]/Cl vssa1
	C157 note_0/ip_bar_0[0]/ip_pbw_0[6]/Cl vssa1 3.32f
	**note_0/ip_bar_0[0]/ip_pbw_0[6]/Cl vssa1
	C158 note_0/ip_bar_0[0]/ip_pbw_0[7]/Cl vssa1 3.32f
	**note_0/ip_bar_0[0]/ip_pbw_0[7]/Cl vssa1
	C159 note_0/ip_bar_0[0]/ip_pbw_0[8]/Cl vssa1 3.32f
	**note_0/ip_bar_0[0]/ip_pbw_0[8]/Cl vssa1
	C160 note_0/ip_bar_0[0]/ip_pbw_0[9]/Cl vssa1 3.32f
	**note_0/ip_bar_0[0]/ip_pbw_0[9]/Cl vssa1
	C161 note_0/ip_bar_0[0]/ip_pbw_0[10]/Cl vssa1 3.32f
	**note_0/ip_bar_0[0]/ip_pbw_0[10]/Cl vssa1
	C162 note_0/ip_bar_0[0]/ip_pbw_0[11]/Cl vssa1 3.32f
	**note_0/ip_bar_0[0]/ip_pbw_0[11]/Cl vssa1
	C163 note_0/ip_bar_0[0]/ip_pbw_0[12]/Cl vssa1 3.32f
	**note_0/ip_bar_0[0]/ip_pbw_0[12]/Cl vssa1
	C164 note_0/ip_bar_0[0]/ip_pbw_0[13]/Cl vssa1 3.32f
	**note_0/ip_bar_0[0]/ip_pbw_0[13]/Cl vssa1
	C165 note_0/ip_bar_0[0]/ip_pbw_0[14]/Cl vssa1 3.31f
	**note_0/ip_bar_0[0]/ip_pbw_0[14]/Cl vssa1
	C166 note_0/ip_bar_0[0]/ip_q2n_1[1]/Cl vssa1 3.3f
	**note_0/ip_bar_0[0]/ip_q2n_1[1]/Cl vssa1
	C167 note_0/ip_bar_0[0]/ip_q2n_1[2]/Cl vssa1 3.3f
	**note_0/ip_bar_0[0]/ip_q2n_1[2]/Cl vssa1
	C168 note_0/ip_bar_0[0]/ip_q2n_1[3]/Cl vssa1 3.3f
	**note_0/ip_bar_0[0]/ip_q2n_1[3]/Cl vssa1
	C169 note_0/ip_bar_0[0]/ip_q2n_1[4]/Cl vssa1 3.3f
	**note_0/ip_bar_0[0]/ip_q2n_1[4]/Cl vssa1
	C170 note_0/ip_bar_0[0]/ip_q2n_1[5]/Cl vssa1 2.68f
	**note_0/ip_bar_0[0]/ip_q2n_1[5]/Cl vssa1
	C171 note_0/ip_bar_0[0]/ip_q2n_1[6]/Cl vssa1 2.64f
	**note_0/ip_bar_0[0]/ip_q2n_1[6]/Cl vssa1
	C172 note_0/ip_bar_0[0]/ip_q2w_0/Cl2 vssa1 6.7f
	**note_0/ip_bar_0[0]/ip_q2w_0/Cl2 vssa1
	C173 note_0/ip_bar_0[0]/ip_q2w_0/Cl vssa1 2.59f
	**note_0/ip_bar_0[0]/ip_q2w_0/Cl vssa1
	C174 note_0/ip_bar_0[1]/Jx note_0/ip_bar_0[1]/Jy 5f
	**note_0/ip_bar_0[1]/Jx note_0/ip_bar_0[1]/Jy
	C175 note_0/ip_bar_0[1]/Jy vdda2 5.42f
	**note_0/ip_bar_0[1]/Jy vdda2
	C176 note_0/ip_bar_0[1]/S0CM vssa1 3.07f
	**note_0/ip_bar_0[1]/S0CM vssa1
	C177 note_0/ip_bar_0[1]/S0TM vssa1 2.83f
	**note_0/ip_bar_0[1]/S0TM vssa1
	C178 note_0/ip_bar_0[1]/ip_cgn_0[0]/Clx vssa1 2.11f
	**note_0/ip_bar_0[1]/ip_cgn_0[0]/Clx vssa1
	C179 note_0/ip_bar_0[1]/ip_cgn_0[1]/Clx vssa1 2.11f
	**note_0/ip_bar_0[1]/ip_cgn_0[1]/Clx vssa1
	C180 note_0/ip_bar_0[1]/ip_cgn_0[2]/Clx vssa1 2.11f
	**note_0/ip_bar_0[1]/ip_cgn_0[2]/Clx vssa1
	C181 note_0/ip_bar_0[1]/ip_cgn_0[3]/Clx vssa1 2.11f
	**note_0/ip_bar_0[1]/ip_cgn_0[3]/Clx vssa1
	C182 note_0/ip_bar_0[1]/ip_cgn_0[4]/Clx vssa1 2.11f
	**note_0/ip_bar_0[1]/ip_cgn_0[4]/Clx vssa1
	C183 note_0/ip_bar_0[1]/ip_clb_0/Bp1C note_0/ip_bar_0[1]/ip_clb_0/Bp1T 7.49f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp1C note_0/ip_bar_0[1]/ip_clb_0/Bp1T
	C184 note_0/ip_bar_0[1]/ip_clb_0/Bp1C note_0/ip_bar_0[1]/ip_clb_0/Bp2C 15.1f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp1C note_0/ip_bar_0[1]/ip_clb_0/Bp2C
	C185 note_0/ip_bar_0[1]/ip_clb_0/Bp1C note_0/ip_bar_0[1]/ip_clb_0/Bp2T 2f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp1C note_0/ip_bar_0[1]/ip_clb_0/Bp2T
	C186 note_0/ip_bar_0[1]/ip_clb_0/Bp1C note_0/ip_bar_0[1]/ip_clb_0/Jx 2.08f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp1C note_0/ip_bar_0[1]/ip_clb_0/Jx
	C187 note_0/ip_bar_0[1]/ip_clb_0/Bp1C note_0/ip_bar_0[1]/ip_clb_0/Jy 2.29f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp1C note_0/ip_bar_0[1]/ip_clb_0/Jy
	C188 note_0/ip_bar_0[1]/ip_clb_0/Bp1C note_0/ip_bar_0[1]/ip_clb_0/p0C 13.6f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp1C note_0/ip_bar_0[1]/ip_clb_0/p0C
	C189 note_0/ip_bar_0[1]/ip_clb_0/Bp1C vdda2 4.14f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp1C vdda2
	C190 note_0/ip_bar_0[1]/ip_clb_0/Bp1C vssa1 9.35f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp1C vssa1
	C191 note_0/ip_bar_0[1]/ip_clb_0/Bp1T note_0/ip_bar_0[1]/ip_clb_0/Bp2T 15.4f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp1T note_0/ip_bar_0[1]/ip_clb_0/Bp2T
	C192 note_0/ip_bar_0[1]/ip_clb_0/Bp1T note_0/ip_bar_0[1]/ip_clb_0/Jx 3.95f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp1T note_0/ip_bar_0[1]/ip_clb_0/Jx
	C193 note_0/ip_bar_0[1]/ip_clb_0/Bp1T note_0/ip_bar_0[1]/ip_clb_0/p0T 13.6f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp1T note_0/ip_bar_0[1]/ip_clb_0/p0T
	C194 note_0/ip_bar_0[1]/ip_clb_0/Bp1T vdda2 3.14f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp1T vdda2
	C195 note_0/ip_bar_0[1]/ip_clb_0/Bp1T vssa1 11.2f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp1T vssa1
	C196 note_0/ip_bar_0[1]/ip_clb_0/Bp2C note_0/ip_bar_0[1]/ip_clb_0/Bp2T 7.49f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp2C note_0/ip_bar_0[1]/ip_clb_0/Bp2T
	C197 note_0/ip_bar_0[1]/ip_clb_0/Bp2C note_0/ip_bar_0[1]/ip_clb_0/Bp3C 15.1f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp2C note_0/ip_bar_0[1]/ip_clb_0/Bp3C
	C198 note_0/ip_bar_0[1]/ip_clb_0/Bp2C note_0/ip_bar_0[1]/ip_clb_0/Bp3T 2f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp2C note_0/ip_bar_0[1]/ip_clb_0/Bp3T
	C199 note_0/ip_bar_0[1]/ip_clb_0/Bp2C note_0/ip_bar_0[1]/ip_clb_0/Jx 2.22f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp2C note_0/ip_bar_0[1]/ip_clb_0/Jx
	C200 note_0/ip_bar_0[1]/ip_clb_0/Bp2C vdda2 4.14f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp2C vdda2
	C201 note_0/ip_bar_0[1]/ip_clb_0/Bp2C vssa1 9.31f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp2C vssa1
	C202 note_0/ip_bar_0[1]/ip_clb_0/Bp2T note_0/ip_bar_0[1]/ip_clb_0/Bp3T 15.4f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp2T note_0/ip_bar_0[1]/ip_clb_0/Bp3T
	C203 note_0/ip_bar_0[1]/ip_clb_0/Bp2T vdda2 3.14f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp2T vdda2
	C204 note_0/ip_bar_0[1]/ip_clb_0/Bp2T vssa1 11.1f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp2T vssa1
	C205 note_0/ip_bar_0[1]/ip_clb_0/Bp3C note_0/ip_bar_0[1]/ip_clb_0/Bp3T 7.49f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp3C note_0/ip_bar_0[1]/ip_clb_0/Bp3T
	C206 note_0/ip_bar_0[1]/ip_clb_0/Bp3C note_0/ip_bar_0[1]/ip_clb_0/Jx 2.16f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp3C note_0/ip_bar_0[1]/ip_clb_0/Jx
	C207 note_0/ip_bar_0[1]/ip_clb_0/Bp3C note_0/ip_bar_0[1]/ip_clb_0/p0C 2f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp3C note_0/ip_bar_0[1]/ip_clb_0/p0C
	C208 note_0/ip_bar_0[1]/ip_clb_0/Bp3C note_0/ip_bar_0[1]/ip_clb_0/p0T 15.1f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp3C note_0/ip_bar_0[1]/ip_clb_0/p0T
	C209 note_0/ip_bar_0[1]/ip_clb_0/Bp3C vdda2 4.14f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp3C vdda2
	C210 note_0/ip_bar_0[1]/ip_clb_0/Bp3C vssa1 9.35f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp3C vssa1
	C211 note_0/ip_bar_0[1]/ip_clb_0/Bp3T note_0/ip_bar_0[1]/ip_clb_0/p0C 15.4f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp3T note_0/ip_bar_0[1]/ip_clb_0/p0C
	C212 note_0/ip_bar_0[1]/ip_clb_0/Bp3T vdda2 3.14f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp3T vdda2
	C213 note_0/ip_bar_0[1]/ip_clb_0/Bp3T vssa1 11f
	**note_0/ip_bar_0[1]/ip_clb_0/Bp3T vssa1
	C214 note_0/ip_bar_0[1]/ip_clb_0/Cl1 vssa1 3.32f
	**note_0/ip_bar_0[1]/ip_clb_0/Cl1 vssa1
	C215 note_0/ip_bar_0[1]/ip_clb_0/Cl2 vssa1 6.03f
	**note_0/ip_bar_0[1]/ip_clb_0/Cl2 vssa1
	C216 note_0/ip_bar_0[1]/ip_clb_0/Jx note_0/ip_bar_0[1]/ip_clb_0/Jy 14.8f
	**note_0/ip_bar_0[1]/ip_clb_0/Jx note_0/ip_bar_0[1]/ip_clb_0/Jy
	C217 note_0/ip_bar_0[1]/ip_clb_0/Jx note_0/ip_bar_0[1]/ip_clb_0/p0C 3.95f
	**note_0/ip_bar_0[1]/ip_clb_0/Jx note_0/ip_bar_0[1]/ip_clb_0/p0C
	C218 note_0/ip_bar_0[1]/ip_clb_0/Jx note_0/ip_bar_0[1]/ip_clb_0/p0T 2.42f
	**note_0/ip_bar_0[1]/ip_clb_0/Jx note_0/ip_bar_0[1]/ip_clb_0/p0T
	C219 note_0/ip_bar_0[1]/ip_clb_0/Jx vssa1 5.51f
	**note_0/ip_bar_0[1]/ip_clb_0/Jx vssa1
	C220 note_0/ip_bar_0[1]/ip_clb_0/Jy note_0/ip_bar_0[1]/ip_clb_0/p0T 2.29f
	**note_0/ip_bar_0[1]/ip_clb_0/Jy note_0/ip_bar_0[1]/ip_clb_0/p0T
	C221 note_0/ip_bar_0[1]/ip_clb_0/Jy vdda2 15.8f
	**note_0/ip_bar_0[1]/ip_clb_0/Jy vdda2
	C222 note_0/ip_bar_0[1]/ip_clb_0/Jy vssa1 3.23f
	**note_0/ip_bar_0[1]/ip_clb_0/Jy vssa1
	C223 note_0/ip_bar_0[1]/ip_clb_0/p0C note_0/ip_bar_0[1]/ip_clb_0/p0T 7.49f
	**note_0/ip_bar_0[1]/ip_clb_0/p0C note_0/ip_bar_0[1]/ip_clb_0/p0T
	C224 note_0/ip_bar_0[1]/ip_clb_0/p0C vdda2 3.14f
	**note_0/ip_bar_0[1]/ip_clb_0/p0C vdda2
	C225 note_0/ip_bar_0[1]/ip_clb_0/p0C vssa1 11f
	**note_0/ip_bar_0[1]/ip_clb_0/p0C vssa1
	C226 note_0/ip_bar_0[1]/ip_clb_0/p0T vdda2 4.14f
	**note_0/ip_bar_0[1]/ip_clb_0/p0T vdda2
	C227 note_0/ip_bar_0[1]/ip_clb_0/p0T vssa1 9.07f
	**note_0/ip_bar_0[1]/ip_clb_0/p0T vssa1
	C228 note_0/ip_bar_0[1]/ip_pbw_0[1]/Cl vssa1 3.31f
	**note_0/ip_bar_0[1]/ip_pbw_0[1]/Cl vssa1
	C229 note_0/ip_bar_0[1]/ip_pbw_0[2]/Cl vssa1 3.31f
	**note_0/ip_bar_0[1]/ip_pbw_0[2]/Cl vssa1
	C230 note_0/ip_bar_0[1]/ip_pbw_0[3]/Cl vssa1 3.32f
	**note_0/ip_bar_0[1]/ip_pbw_0[3]/Cl vssa1
	C231 note_0/ip_bar_0[1]/ip_pbw_0[4]/Cl vssa1 3.32f
	**note_0/ip_bar_0[1]/ip_pbw_0[4]/Cl vssa1
	C232 note_0/ip_bar_0[1]/ip_pbw_0[5]/Cl vssa1 3.32f
	**note_0/ip_bar_0[1]/ip_pbw_0[5]/Cl vssa1
	C233 note_0/ip_bar_0[1]/ip_pbw_0[6]/Cl vssa1 3.32f
	**note_0/ip_bar_0[1]/ip_pbw_0[6]/Cl vssa1
	C234 note_0/ip_bar_0[1]/ip_pbw_0[7]/Cl vssa1 3.32f
	**note_0/ip_bar_0[1]/ip_pbw_0[7]/Cl vssa1
	C235 note_0/ip_bar_0[1]/ip_pbw_0[8]/Cl vssa1 3.32f
	**note_0/ip_bar_0[1]/ip_pbw_0[8]/Cl vssa1
	C236 note_0/ip_bar_0[1]/ip_pbw_0[9]/Cl vssa1 3.32f
	**note_0/ip_bar_0[1]/ip_pbw_0[9]/Cl vssa1
	C237 note_0/ip_bar_0[1]/ip_pbw_0[10]/Cl vssa1 3.32f
	**note_0/ip_bar_0[1]/ip_pbw_0[10]/Cl vssa1
	C238 note_0/ip_bar_0[1]/ip_pbw_0[11]/Cl vssa1 3.32f
	**note_0/ip_bar_0[1]/ip_pbw_0[11]/Cl vssa1
	C239 note_0/ip_bar_0[1]/ip_pbw_0[12]/Cl vssa1 3.32f
	**note_0/ip_bar_0[1]/ip_pbw_0[12]/Cl vssa1
	C240 note_0/ip_bar_0[1]/ip_pbw_0[13]/Cl vssa1 3.32f
	**note_0/ip_bar_0[1]/ip_pbw_0[13]/Cl vssa1
	C241 note_0/ip_bar_0[1]/ip_pbw_0[14]/Cl vssa1 3.31f
	**note_0/ip_bar_0[1]/ip_pbw_0[14]/Cl vssa1
	C242 note_0/ip_bar_0[1]/ip_q2n_1[1]/Cl vssa1 3.3f
	**note_0/ip_bar_0[1]/ip_q2n_1[1]/Cl vssa1
	C243 note_0/ip_bar_0[1]/ip_q2n_1[2]/Cl vssa1 3.3f
	**note_0/ip_bar_0[1]/ip_q2n_1[2]/Cl vssa1
	C244 note_0/ip_bar_0[1]/ip_q2n_1[3]/Cl vssa1 3.3f
	**note_0/ip_bar_0[1]/ip_q2n_1[3]/Cl vssa1
	C245 note_0/ip_bar_0[1]/ip_q2n_1[4]/Cl vssa1 3.3f
	**note_0/ip_bar_0[1]/ip_q2n_1[4]/Cl vssa1
	C246 note_0/ip_bar_0[1]/ip_q2n_1[5]/Cl vssa1 2.68f
	**note_0/ip_bar_0[1]/ip_q2n_1[5]/Cl vssa1
	C247 note_0/ip_bar_0[1]/ip_q2n_1[6]/Cl vssa1 2.64f
	**note_0/ip_bar_0[1]/ip_q2n_1[6]/Cl vssa1
	C248 note_0/ip_bar_0[1]/ip_q2w_0/Cl2 vssa1 6.7f
	**note_0/ip_bar_0[1]/ip_q2w_0/Cl2 vssa1
	C249 note_0/ip_bar_0[1]/ip_q2w_0/Cl vssa1 2.59f
	**note_0/ip_bar_0[1]/ip_q2w_0/Cl vssa1
	C250 note_0/ip_bar_0[2]/Jx note_0/ip_bar_0[2]/Jy 5f
	**note_0/ip_bar_0[2]/Jx note_0/ip_bar_0[2]/Jy
	C251 note_0/ip_bar_0[2]/Jy vdda2 5.42f
	**note_0/ip_bar_0[2]/Jy vdda2
	C252 note_0/ip_bar_0[2]/S0CM vssa1 3.07f
	**note_0/ip_bar_0[2]/S0CM vssa1
	C253 note_0/ip_bar_0[2]/S0TM vssa1 2.83f
	**note_0/ip_bar_0[2]/S0TM vssa1
	C254 note_0/ip_bar_0[2]/ip_cgn_0[0]/Clx vssa1 2.11f
	**note_0/ip_bar_0[2]/ip_cgn_0[0]/Clx vssa1
	C255 note_0/ip_bar_0[2]/ip_cgn_0[1]/Clx vssa1 2.11f
	**note_0/ip_bar_0[2]/ip_cgn_0[1]/Clx vssa1
	C256 note_0/ip_bar_0[2]/ip_cgn_0[2]/Clx vssa1 2.11f
	**note_0/ip_bar_0[2]/ip_cgn_0[2]/Clx vssa1
	C257 note_0/ip_bar_0[2]/ip_cgn_0[3]/Clx vssa1 2.11f
	**note_0/ip_bar_0[2]/ip_cgn_0[3]/Clx vssa1
	C258 note_0/ip_bar_0[2]/ip_cgn_0[4]/Clx vssa1 2.11f
	**note_0/ip_bar_0[2]/ip_cgn_0[4]/Clx vssa1
	C259 note_0/ip_bar_0[2]/ip_clb_0/Bp1C note_0/ip_bar_0[2]/ip_clb_0/Bp1T 7.49f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp1C note_0/ip_bar_0[2]/ip_clb_0/Bp1T
	C260 note_0/ip_bar_0[2]/ip_clb_0/Bp1C note_0/ip_bar_0[2]/ip_clb_0/Bp2C 15.1f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp1C note_0/ip_bar_0[2]/ip_clb_0/Bp2C
	C261 note_0/ip_bar_0[2]/ip_clb_0/Bp1C note_0/ip_bar_0[2]/ip_clb_0/Bp2T 2f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp1C note_0/ip_bar_0[2]/ip_clb_0/Bp2T
	C262 note_0/ip_bar_0[2]/ip_clb_0/Bp1C note_0/ip_bar_0[2]/ip_clb_0/Jx 2.08f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp1C note_0/ip_bar_0[2]/ip_clb_0/Jx
	C263 note_0/ip_bar_0[2]/ip_clb_0/Bp1C note_0/ip_bar_0[2]/ip_clb_0/Jy 2.29f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp1C note_0/ip_bar_0[2]/ip_clb_0/Jy
	C264 note_0/ip_bar_0[2]/ip_clb_0/Bp1C note_0/ip_bar_0[2]/ip_clb_0/p0C 13.6f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp1C note_0/ip_bar_0[2]/ip_clb_0/p0C
	C265 note_0/ip_bar_0[2]/ip_clb_0/Bp1C vdda2 4.14f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp1C vdda2
	C266 note_0/ip_bar_0[2]/ip_clb_0/Bp1C vssa1 9.35f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp1C vssa1
	C267 note_0/ip_bar_0[2]/ip_clb_0/Bp1T note_0/ip_bar_0[2]/ip_clb_0/Bp2T 15.4f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp1T note_0/ip_bar_0[2]/ip_clb_0/Bp2T
	C268 note_0/ip_bar_0[2]/ip_clb_0/Bp1T note_0/ip_bar_0[2]/ip_clb_0/Jx 3.95f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp1T note_0/ip_bar_0[2]/ip_clb_0/Jx
	C269 note_0/ip_bar_0[2]/ip_clb_0/Bp1T note_0/ip_bar_0[2]/ip_clb_0/p0T 13.6f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp1T note_0/ip_bar_0[2]/ip_clb_0/p0T
	C270 note_0/ip_bar_0[2]/ip_clb_0/Bp1T vdda2 3.14f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp1T vdda2
	C271 note_0/ip_bar_0[2]/ip_clb_0/Bp1T vssa1 11.2f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp1T vssa1
	C272 note_0/ip_bar_0[2]/ip_clb_0/Bp2C note_0/ip_bar_0[2]/ip_clb_0/Bp2T 7.49f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp2C note_0/ip_bar_0[2]/ip_clb_0/Bp2T
	C273 note_0/ip_bar_0[2]/ip_clb_0/Bp2C note_0/ip_bar_0[2]/ip_clb_0/Bp3C 15.1f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp2C note_0/ip_bar_0[2]/ip_clb_0/Bp3C
	C274 note_0/ip_bar_0[2]/ip_clb_0/Bp2C note_0/ip_bar_0[2]/ip_clb_0/Bp3T 2f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp2C note_0/ip_bar_0[2]/ip_clb_0/Bp3T
	C275 note_0/ip_bar_0[2]/ip_clb_0/Bp2C note_0/ip_bar_0[2]/ip_clb_0/Jx 2.22f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp2C note_0/ip_bar_0[2]/ip_clb_0/Jx
	C276 note_0/ip_bar_0[2]/ip_clb_0/Bp2C vdda2 4.14f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp2C vdda2
	C277 note_0/ip_bar_0[2]/ip_clb_0/Bp2C vssa1 9.31f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp2C vssa1
	C278 note_0/ip_bar_0[2]/ip_clb_0/Bp2T note_0/ip_bar_0[2]/ip_clb_0/Bp3T 15.4f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp2T note_0/ip_bar_0[2]/ip_clb_0/Bp3T
	C279 note_0/ip_bar_0[2]/ip_clb_0/Bp2T vdda2 3.14f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp2T vdda2
	C280 note_0/ip_bar_0[2]/ip_clb_0/Bp2T vssa1 11.1f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp2T vssa1
	C281 note_0/ip_bar_0[2]/ip_clb_0/Bp3C note_0/ip_bar_0[2]/ip_clb_0/Bp3T 7.49f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp3C note_0/ip_bar_0[2]/ip_clb_0/Bp3T
	C282 note_0/ip_bar_0[2]/ip_clb_0/Bp3C note_0/ip_bar_0[2]/ip_clb_0/Jx 2.16f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp3C note_0/ip_bar_0[2]/ip_clb_0/Jx
	C283 note_0/ip_bar_0[2]/ip_clb_0/Bp3C note_0/ip_bar_0[2]/ip_clb_0/p0C 2f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp3C note_0/ip_bar_0[2]/ip_clb_0/p0C
	C284 note_0/ip_bar_0[2]/ip_clb_0/Bp3C note_0/ip_bar_0[2]/ip_clb_0/p0T 15.1f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp3C note_0/ip_bar_0[2]/ip_clb_0/p0T
	C285 note_0/ip_bar_0[2]/ip_clb_0/Bp3C vdda2 4.14f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp3C vdda2
	C286 note_0/ip_bar_0[2]/ip_clb_0/Bp3C vssa1 9.35f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp3C vssa1
	C287 note_0/ip_bar_0[2]/ip_clb_0/Bp3T note_0/ip_bar_0[2]/ip_clb_0/p0C 15.4f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp3T note_0/ip_bar_0[2]/ip_clb_0/p0C
	C288 note_0/ip_bar_0[2]/ip_clb_0/Bp3T vdda2 3.14f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp3T vdda2
	C289 note_0/ip_bar_0[2]/ip_clb_0/Bp3T vssa1 11f
	**note_0/ip_bar_0[2]/ip_clb_0/Bp3T vssa1
	C290 note_0/ip_bar_0[2]/ip_clb_0/Cl1 vssa1 3.32f
	**note_0/ip_bar_0[2]/ip_clb_0/Cl1 vssa1
	C291 note_0/ip_bar_0[2]/ip_clb_0/Cl2 vssa1 6.03f
	**note_0/ip_bar_0[2]/ip_clb_0/Cl2 vssa1
	C292 note_0/ip_bar_0[2]/ip_clb_0/Jx note_0/ip_bar_0[2]/ip_clb_0/Jy 14.8f
	**note_0/ip_bar_0[2]/ip_clb_0/Jx note_0/ip_bar_0[2]/ip_clb_0/Jy
	C293 note_0/ip_bar_0[2]/ip_clb_0/Jx note_0/ip_bar_0[2]/ip_clb_0/p0C 3.95f
	**note_0/ip_bar_0[2]/ip_clb_0/Jx note_0/ip_bar_0[2]/ip_clb_0/p0C
	C294 note_0/ip_bar_0[2]/ip_clb_0/Jx note_0/ip_bar_0[2]/ip_clb_0/p0T 2.42f
	**note_0/ip_bar_0[2]/ip_clb_0/Jx note_0/ip_bar_0[2]/ip_clb_0/p0T
	C295 note_0/ip_bar_0[2]/ip_clb_0/Jx vssa1 5.51f
	**note_0/ip_bar_0[2]/ip_clb_0/Jx vssa1
	C296 note_0/ip_bar_0[2]/ip_clb_0/Jy note_0/ip_bar_0[2]/ip_clb_0/p0T 2.29f
	**note_0/ip_bar_0[2]/ip_clb_0/Jy note_0/ip_bar_0[2]/ip_clb_0/p0T
	C297 note_0/ip_bar_0[2]/ip_clb_0/Jy vdda2 15.8f
	**note_0/ip_bar_0[2]/ip_clb_0/Jy vdda2
	C298 note_0/ip_bar_0[2]/ip_clb_0/Jy vssa1 3.23f
	**note_0/ip_bar_0[2]/ip_clb_0/Jy vssa1
	C299 note_0/ip_bar_0[2]/ip_clb_0/p0C note_0/ip_bar_0[2]/ip_clb_0/p0T 7.49f
	**note_0/ip_bar_0[2]/ip_clb_0/p0C note_0/ip_bar_0[2]/ip_clb_0/p0T
	C300 note_0/ip_bar_0[2]/ip_clb_0/p0C vdda2 3.14f
	**note_0/ip_bar_0[2]/ip_clb_0/p0C vdda2
	C301 note_0/ip_bar_0[2]/ip_clb_0/p0C vssa1 11f
	**note_0/ip_bar_0[2]/ip_clb_0/p0C vssa1
	C302 note_0/ip_bar_0[2]/ip_clb_0/p0T vdda2 4.14f
	**note_0/ip_bar_0[2]/ip_clb_0/p0T vdda2
	C303 note_0/ip_bar_0[2]/ip_clb_0/p0T vssa1 9.07f
	**note_0/ip_bar_0[2]/ip_clb_0/p0T vssa1
	C304 note_0/ip_bar_0[2]/ip_pbw_0[1]/Cl vssa1 3.31f
	**note_0/ip_bar_0[2]/ip_pbw_0[1]/Cl vssa1
	C305 note_0/ip_bar_0[2]/ip_pbw_0[2]/Cl vssa1 3.31f
	**note_0/ip_bar_0[2]/ip_pbw_0[2]/Cl vssa1
	C306 note_0/ip_bar_0[2]/ip_pbw_0[3]/Cl vssa1 3.32f
	**note_0/ip_bar_0[2]/ip_pbw_0[3]/Cl vssa1
	C307 note_0/ip_bar_0[2]/ip_pbw_0[4]/Cl vssa1 3.32f
	**note_0/ip_bar_0[2]/ip_pbw_0[4]/Cl vssa1
	C308 note_0/ip_bar_0[2]/ip_pbw_0[5]/Cl vssa1 3.32f
	**note_0/ip_bar_0[2]/ip_pbw_0[5]/Cl vssa1
	C309 note_0/ip_bar_0[2]/ip_pbw_0[6]/Cl vssa1 3.32f
	**note_0/ip_bar_0[2]/ip_pbw_0[6]/Cl vssa1
	C310 note_0/ip_bar_0[2]/ip_pbw_0[7]/Cl vssa1 3.32f
	**note_0/ip_bar_0[2]/ip_pbw_0[7]/Cl vssa1
	C311 note_0/ip_bar_0[2]/ip_pbw_0[8]/Cl vssa1 3.32f
	**note_0/ip_bar_0[2]/ip_pbw_0[8]/Cl vssa1
	C312 note_0/ip_bar_0[2]/ip_pbw_0[9]/Cl vssa1 3.32f
	**note_0/ip_bar_0[2]/ip_pbw_0[9]/Cl vssa1
	C313 note_0/ip_bar_0[2]/ip_pbw_0[10]/Cl vssa1 3.32f
	**note_0/ip_bar_0[2]/ip_pbw_0[10]/Cl vssa1
	C314 note_0/ip_bar_0[2]/ip_pbw_0[11]/Cl vssa1 3.32f
	**note_0/ip_bar_0[2]/ip_pbw_0[11]/Cl vssa1
	C315 note_0/ip_bar_0[2]/ip_pbw_0[12]/Cl vssa1 3.32f
	**note_0/ip_bar_0[2]/ip_pbw_0[12]/Cl vssa1
	C316 note_0/ip_bar_0[2]/ip_pbw_0[13]/Cl vssa1 3.32f
	**note_0/ip_bar_0[2]/ip_pbw_0[13]/Cl vssa1
	C317 note_0/ip_bar_0[2]/ip_pbw_0[14]/Cl vssa1 3.31f
	**note_0/ip_bar_0[2]/ip_pbw_0[14]/Cl vssa1
	C318 note_0/ip_bar_0[2]/ip_q2n_1[1]/Cl vssa1 3.3f
	**note_0/ip_bar_0[2]/ip_q2n_1[1]/Cl vssa1
	C319 note_0/ip_bar_0[2]/ip_q2n_1[2]/Cl vssa1 3.3f
	**note_0/ip_bar_0[2]/ip_q2n_1[2]/Cl vssa1
	C320 note_0/ip_bar_0[2]/ip_q2n_1[3]/Cl vssa1 3.3f
	**note_0/ip_bar_0[2]/ip_q2n_1[3]/Cl vssa1
	C321 note_0/ip_bar_0[2]/ip_q2n_1[4]/Cl vssa1 3.3f
	**note_0/ip_bar_0[2]/ip_q2n_1[4]/Cl vssa1
	C322 note_0/ip_bar_0[2]/ip_q2n_1[5]/Cl vssa1 2.68f
	**note_0/ip_bar_0[2]/ip_q2n_1[5]/Cl vssa1
	C323 note_0/ip_bar_0[2]/ip_q2n_1[6]/Cl vssa1 2.64f
	**note_0/ip_bar_0[2]/ip_q2n_1[6]/Cl vssa1
	C324 note_0/ip_bar_0[2]/ip_q2w_0/Cl2 vssa1 6.7f
	**note_0/ip_bar_0[2]/ip_q2w_0/Cl2 vssa1
	C325 note_0/ip_bar_0[2]/ip_q2w_0/Cl vssa1 2.59f
	**note_0/ip_bar_0[2]/ip_q2w_0/Cl vssa1
	C326 note_0/ip_swp_hi/BC vssa1 4.56f
	**note_0/ip_swp_hi/BC vssa1
	C327 note_0/ip_swp_hi/BT vssa1 2.7f
	**note_0/ip_swp_hi/BT vssa1
	C328 note_0/ip_swp_lo/AC vssa1 4.55f
	**note_0/ip_swp_lo/AC vssa1
	C329 note_0/ip_swp_lo/AT vssa1 3.04f
	**note_0/ip_swp_lo/AT vssa1
	C330 vccd1 vssa1 15.5f
	**vccd1 vssa1
	C331 vccd2 vssa1 15.5f
	**vccd2 vssa1
	C332 vdda1 vssa1 0.156p
	**vdda1 vssa1
	C333 vdda2 vssa1 2.31p
	**vdda2 vssa1
	C334 vssa1 vssa2 15.5f
	**vssa1 vssa2
	C335 vssa1 vssd1 15.5f
	**vssa1 vssd1
	C336 vssa1 vssd2 15.5f
	**vssa1 vssd2
```

</details>

For more information, please see <a href="http://revcomp.org">revcomp.org</a>.
