**NOT A PASCAL!!!! IT'S A FREE PASCAL!!**
``` Pascal
Program Fib;

    var x,y,q,z,i:integer;
    
    begin
        x:= 0;
        y:= 1;
        write('Введите номер числа из последовательности: ');
        read(z);
        for i := 3 to z do
        begin
            q := y;
            y := x+y;
            x := q;
        end;
        writeln('Число под номером ', z, ' Равно ', y);
end.
```

