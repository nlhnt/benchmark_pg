## nim c
`nim c --threads:on test1.nim`  
`Measure-Command {.\test1.exe 18}`

## nim c --opt:speed
`nim c --opt:speed --threads:on -o:test1_speed_opt.exe test1.nim`  
`Measure-Command {.\test1_speed_opt.exe 18}`