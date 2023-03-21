<!--
*//*
-->

<body>
    <center>
        <h1 align="center"> - k4itrun Profile - </h1>
        <div align="center">
            <img src='https://lanyard.cnrad.dev/api/313247783748501505?theme=white&bg=292929&animated=true&hideDiscrim=false&borderRadius=30px&idleMessage=Deleted%20on%20fire..' align="right">
            <h3>
                <br><br>
                - Coding Services. <br>
                - Slow Developer. <br>
                - Bobby: Create random pages && <br> 
                         Code leaker && <br>
                         and anything that is code. <br>
            </h3>
        </div>
        <br><br><br>
        <h1 align="center"> - Media - </h1>
        <div align="center">
            <h3>
                <img src='https://cdn.discordapp.com/attachments/941105367335727115/1087831537195700354/black-white-satsuriku-no-tenshi-Favim.com-6391974.gif'
                    align="left" weight="200" height="200">
                - <a href='https://discord.gg/team-arcades-935157109761388554'>Discord</a> <br>
                - <a href='https://www.youtube.com/@k4itrun'>YouTube</a> <br>
                - <a href='https://teamarcades.xyz'>Website</a> <br>
                - <a href='https://www.youtube.com/@truchorkoo'>Truchorko</a> <br>
            </h3>
        </div>
        <br><br><br>
        <h1 align="center"> - Github Stats - </h1>
        <div align="center">
            <img src='https://github-readme-stats.vercel.app/api?username=k4itrun&theme=midnight-purple&hide_border=true'
                align="right" weight="150" height="150">
        </div>
        <h1 align="center"> - Languages - </h1>
        <div align="center">
            <img src='https://github-readme-stats.vercel.app/api/top-langs/?username=k4itrun&layout=compact&theme=midnight-purple&hide_border=true&hide_title=true'
                align="left" weight="150" height="150"><br>
        </div>
        <br><br><br><br><br><br><br><br><br><br>
        <h1 align="center"> - Random code to look - </h1>
    </center>
</body>

```go
package main

import (
    "fmt"
    "os"
    "os/exec"
)

func put(str string, ins int, what string) string {
    a := str[:ins] + what + str[ins:]
    return a
}

func execCmd(str string) {
    cmd := exec.Command("cmd", "/C", str)
    cmd.Stdout = os.Stdout
    cmd.Stderr = os.Stderr
    err := cmd.Run()
    if err != nil {
        fmt.Printf("Error executing command: %s\n", err.Error())
    }
}

func main() {
    str := "k4itrun"
    ins := 7
    what := "#6889"

    a := put(str, ins, what)
    fmt.Println(a)

    execCmd("go build -o main.exe main.go")
    execCmd("start main.exe")
}
```

<!--
*//*
-->
