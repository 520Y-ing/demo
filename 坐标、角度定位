
(function (){
        let A = {X:0,Y:0}
        let B = {X:4,Y:0}
        let C = {X:4,Y:4}
        var AB = Math.sqrt(Math.pow(A.X - B.X, 2) + Math.pow(A.Y - B.Y, 2));
        var AC = Math.sqrt(Math.pow(A.X - C.X, 2) + Math.pow(A.Y - C.Y, 2));
        var BC = Math.sqrt(Math.pow(B.X - C.X, 2) + Math.pow(B.Y - C.Y, 2));
        var cosA = (
                    Math.pow(AB, 2) + Math.pow(AC, 2) - Math.pow(BC, 2)
                  ) / (
                    2 * AB * AC
                  );
        var angleA = Math.round( Math.acos(cosA) * 180 / Math.PI );
        console.log(angleA)
        // 得到angleA角度：45°
        
        /*
            AB      = 开根( (A.X-B.X)² + (A.Y-B.Y)² ）
            AC      =       A.X-C.X      A.Y-C.Y
            BC      =       B.X-C.X      B.Y-C.Y
            consA   = (AB²+AC²-BC²) / (2*AB*AC)
            angleA  = Math.acos(cosA)*180/Math.PI
        */
})()
