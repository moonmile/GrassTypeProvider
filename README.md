������Ƒ��A���Ƃ��܂��ˌ^����Grass�^�v���o�C�_�[
======================
������Ƒ��A���Ƃ��܂��ˌ^����Grass�����S��...�B


�T���v��
--------
```fsharp:Script.fsx
#r @".\bin\Debug\GrassTypeProvider.dll"
open GrassTypeProvider

type Grass1 = Grass<"wvwwWWwWWWwvWwwwwWWwWWWwWWWWwWWWWWwWWWWWWwWWWWWWWwWwwwwwwwwwwwwWWWwWWWWWwWWWWWWWwWWWWWWWWWwWWWWWWWWWWWWwWWWWWWWWWWWWWWWWWwWWWWWWWWWWWWwWWWWWWWWWWWWWWWWWwwwwwwwwwwwwwwwwwwWwwwwwWWwwwwWWWwwww">
let grass1 = new Grass1()
grass1.Run() // orz
grass1.Value |> printfn "%s" // orz

type Grass2 = Grass<"wvwwWWwWWWwvWwwwwWWwWWWwWWWWwWWWWWwWWWWWWwWWWWWWWwWwwwwwwwwwwwwWWWWwWWWWWWWwWWWWWWWWWWWWWWwWWWWWWWWWWWwwWWWWWWWWWWwwWWWWWWWWWWWWwWWWWWWWWWWwwWWWWWWWWWWwwwwwwWWWWWWWWWWWWWWWwWWWWWWWWWWWWWWWWWWWWWwWWWWWWWWWWWWWWWWWWwwWWWWWWWWWWWWWWWWWwwWWWWWWWWWWWWWWWWWwwwwwWWWWWWWWWWWWWWWWWWWWwwWWWWWWWWWWWWWWWWWWWWWWwWWWWWWWWWWWWWWWWWWWWWWWWWwwwwwwwwwwwwwwwwwwwwwwwwwwWwwwwwwwwwwWWwwwwwwwWWWwwwwwwwWWWWwWWWWWwwwwwwwwWWWWWWwwwwwwwwwwwwwwwwWWWWWWWwwwwwwwwwwwwwwwwwwwwWWWWWWWWwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwWWWWWWWWWwwwwWWWWWWWWWWwwwwwwwwwwwWWWWWWWWWWWwwwwwwwWWWWWWWWWWWWwwwwwwwwwwwwwwwwwwWWWWWWWWWWWWWwwwwwwwwwwwwwwwwwwwwwwwww">
let grass2 = new Grass2()
grass2.Run() // Hello, world!
grass2.Value |> printfn "%s" // Hello, world!

type Grass3 = Grass<"wwwwvwvwwWWwvwwWwwvwwwwWWWwwWwwWWWWWWwwwwWwwvwWWwWwwvwWWWwwwwwWwwwwwwWWwWWWwWWWWWWwWWWWWWWWwwwWwwWWWWWWWWWWwWwwwwwWWWWWWWWWWWwwwwwWWWWWWWWWWWWwwwwWWWWWWWWWWWWWwwwWWWWWWWWWWWWWWwwwWWWWWWWWWWWWWWWwWWWWWWWWWWWWWWWWWWwwwWwwwwwwwwwwwwwwWWWWWWWWWWWWWWWWWWWwwwwwwwwWwwWWWWWWWWWWWWWWWWWWWWWWWWwwwwwwwwwwwwwwwwwwwwwwwwWwwwwwwwwwwwwwwwwwwwwwwwwwwwwwWWwwwwwwwwwwwwwwwwwwwwwwww��wwwwwWWWWWWWWWWWWWWWwWwwwWWWW�킢WWWWWWWwwwWwwWWWWWWWWWWWWwwww���wWwwwwwwwWWWWWWWWWWWWWWWWWwwww����wwwWwwWWWWWWWWWWWWWWWWWWwwwww��wwwwWwwWWWWWWWWWWWWWWWWWWWWW��WWWWWWWWWwwwwwwwwwwwWwwWWWWWWW��WWWWWWWWWwwwwwwwwwwwwwWwwwwwwwwwwwwwwwWWWWWWWWWWWWWWWWWwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwWwwwwwwwwwwwwwwWWwwwwwwwwwWWWwwWWWWwwwwwwwwwwwwwwwWWWWWwwWWWWWWwwwwWWWWWWWwwWWWWWWWWwwwwWWWWWWWWWwwWWWWWWWWWWwwwwwwwwwwwwwWWWWWWWWWWWWWWWWWWWWWWWWWWWWwwwwwwwwwwwWwwwWWwwwwwwwwwwwwwwwwwwWWWwwWWWWwwwwwwwwwwwwwwwwwwwwwwwwWWWWWwwWWWWWWwwwwwwwWWWWWWWwwWWWWWWWWwwwwwwWWWWWWWWWwwWWWWWWWWWWwwwwwwWWWWWWWWWWWwwwwwwwwwwwwwwwwwwwwwww">
let grass3 = new Grass3()
grass3.Run() // �͂��͂���낷\n
grass3.Value |> printfn "%s" // �͂��͂���낷\n
```

