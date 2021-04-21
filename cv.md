1. Maksim Karaseu 
2. vk.com/dassivemick - VK
   @zdarovanaprimer - TELEGRAM 
   +375336619494 - mobile phone
3. Student of the second course in GRSU - Grodno state university. Studying in English on a mathinfo faculty, so i have a good level of english. By documents it is a B2+. Up ot learning new languages to find myself in some of IT directions. Nowadays wanna try IOS development. Very fast learning duo to student life way with infinite deadlines and labs. And at the same time learning by myself. At this time it's a course from Alex Skutarenko about the IOS development and Swift at particular.
4. from 1 - completely new to 5 - perfection 
	c++ - 2
	c# - 3
	java - 2
	js - 3
	html/css - 3
	swift - 3

5.

        func putChessFigure(figure: ChessFigure, chessBoard: inout [String: String]){ // puts figure instead of cell block
                switch figure {
            case (.King, let color, (let row, let line)):
                color == .Black ? chessBoard.updateValue(blackKingCode, forKey: "\(row.rawValue)\(line.rawValue)") : chessBoard.updateValue(whiteKingCode, forKey: "\(row.rawValue)\(line.rawValue)")
            case (.Queen, let color, (let row, let line)):
                color == .Black ? chessBoard.updateValue(blackQueenCode, forKey: "\(row.rawValue)\(line.rawValue)") : chessBoard.updateValue(whiteQueenCode, forKey: "\(row.rawValue)\(line.rawValue)")
            case (.Bishop, let color, (let row, let line)):
                color == .Black ? chessBoard.updateValue(blackBishopCode, forKey: "\(row.rawValue)\(line.rawValue)") : chessBoard.updateValue(whiteBishopCode, forKey: "\(row.rawValue)\(line.rawValue)")
            }
        }

        func putAllFigures(figureArray: [ChessFigure], chessBoard: inout [String: String]) {
            for i in figureArray {
                putChessFigure(figure: i, chessBoard: &chessBoard)
            }
        }

        func makeChessBoardCollection(literals: [String], chessBoard: inout [String: String]) -> [String: String]{
            for i in 1...8 {
                for j in 1...8 {
                    if (i+j)%2 == 0 {
                        chessBoard["\(literals[i])\(j)"] = "\u{25a1}"
                    } else {
                        chessBoard["\(literals[i])\(j)"] = "\u{25a0}"
                    }
                }
            }
            return chessBoard
        }

        func printChessBoard(literals: [String], chessBoard: inout [String: String]) {
            print("  A B C D E F G H")
            for i in 1...8 {
                print("\(9-i) ", terminator: "")
                for j in 1...8 {
                    print("\(chessBoard["\(literals[j])\(9-i)"]!) ", terminator: "")
                }
                print("\(i)", terminator: "")
                print("")
            }
            print("  A B C D E F G H")
        }

        func createChess(){
            var chessBoard = [String: String]()
            let literals = [" ", "A", "B", "C", "D", "E", "F", "G", "H"]
            
            makeChessBoardCollection(literals: literals, chessBoard: &chessBoard)
            putAllFigures(figureArray: figureArray, chessBoard: &chessBoard)
            printChessBoard(literals: literals, chessBoard: &chessBoard)
            
        }

        createChess()
6. frontend(map creating with a syncfusion lybrary and webpage at particular) - https://github.com/PankiHoy/TwitterTrends-1
and lots of labs on frontend too

labs on c#: working with collections, patterns, sorting algorithms, text/json parsing

7. currently a student of GRSU,finishing at 2023

8. basically learning at a university in English, so practice is my everyday routine. like i said earlier, the level is about B2+.


