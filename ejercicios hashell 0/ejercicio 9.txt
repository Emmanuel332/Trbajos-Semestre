divisores :: Int -> [Int]
divisores n = [x | x <- [1..n], n `mod` x == 0]
