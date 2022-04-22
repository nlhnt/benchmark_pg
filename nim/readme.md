## nim c
`nim c --threads:on test1.nim`  
`Measure-Command {.\test1.exe 18}`

## nim c --opt:speed
`nim c --opt:speed --threads:on -o:test1_speed_opt.exe test1.nim`  
`Measure-Command {.\test1_speed_opt.exe 18}`  

## nim c -d:danger  
`nim c -d:danger -o:test1_danger_flag.exe test1.nim`  
`Measure-Command {.\test1_danger_flag.exe 18}`  