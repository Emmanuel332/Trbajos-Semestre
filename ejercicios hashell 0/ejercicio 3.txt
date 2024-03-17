numerosPares :: Int -> [Int]
numerosPares n = [x | x <- [0..n], even x]
