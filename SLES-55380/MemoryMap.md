# Memory mapping

This table describes the memory mapping outside the code segment/area.

This is focused on reclaimed/taken space from unused areas.

NOTE: this may not be accurate to the latest version/commit as it's updated by hand.

| **Start Address** | **End Address** | **Size** | Type | **Description**                                  |
| ----------------- | --------------- | -------- | ---- | ------------------------------------------------ |
| 76D4F0            | 76D50C          | 1C       | Hook | Disable Chip's Messages                          |
| 76D50C            | 76D524          | 18       | Hook | Disable Werehog Battle Music                     |
| 76D524            | 76D534          | 10       | Hook | global font spacing                              |
| 76D534            | 76D570          | 3C       | Free | free space                                       |
| 820478            | 82047C          | 4        | Var  | global font spacing value                        |
| 82047C            | 820480          | 4        | Var  | ultrawide movie player mov_r                     |
| 820480            | 820484          | 4        | Var  | ultrawide movie player mov_l                     |
| 820484            | 820488          | 4        | Var  | NPCTalk X scale for ws/uw                        |
| 820488            | 82048C          | 4        | Var  | NPCTalk X bg translation for uw                  |
| 82048C            | 820500          | 74       | Free | free space                                       |
| 820500            | 820504          | 4        | Var  | "%s\\n" string for printf helpers                |
| 820504            | 82051C          | 18       | Hook | fix NPCTalk rendering                            |
| 82051C            | 82052C          | 10       | Hook | DrawMovieWithPos hook for uw                     |
| 82052C            | 820548          | 1C       | Hook | Sonic Control Remap - enablement check func      |
| 820548            | 82056C          | 24       | Hook | Sonic Control Remap - one-frame button down func |
| 82056C            | 820588          | 1C       | Hook | Sonic Control Remap - current button down func   |
| 820588            | 8205A8          | 20       | Hook | Werehog Unleash prevent drain during cutscenes   |
| 8205A8            | 8205B4          | C        | Hook | 60FPS CCameraChanger dT hook                     |
| 8205B4            | 8205F0          | 3C       | Hook | 60FPS GimSonicSpring per-obj half-rate hack func |
| 8205F0            | 8206D0          | E0       | Free | free space                                       |


