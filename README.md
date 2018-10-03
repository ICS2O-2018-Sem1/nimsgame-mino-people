# nimsgame-mino-people
nimsgame-mino-people created by GitHub Classroom
let item = 0
input.onButtonPressed(Button.A, () => {
    item += -1
    basic.showNumber(item)
})
input.onButtonPressed(Button.B, () => {
    item += -2
    basic.showNumber(item)
})
item = 12
basic.showNumber(item)
basic.forever(() => {
    basic.showLeds(`
        . . . . .
        . # . . #
        . . # # .
        . # . . #
        # . . # .
        `)
})
written in java script
(ilikepythonthough)
