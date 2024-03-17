longitudCadena :: String -> Int
longitudCadena [] = 0
longitudCadena (_:xs) = 1 + longitudCadena xs
