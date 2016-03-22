# isPrime

      function isPrime(num){
        var p,d, array = [], isPrime;
        for(p = 2; p <= num; ++p){
            isPrime = 1;
            for( d = 2; d < p; ++d)
                if(p % d === 0)
                  isPrime = 0;
                if( isPrime !== 0)
                  array.push(p);
        }
       return array;
    }
    
    isPrime(100)
