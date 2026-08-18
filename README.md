# DIWBE-exercicioLogica

int d, m, a, nasc;
string mensagem="";


Console.WriteLine("Digite o ano do seu nascimento:");
a = int.Parse(Console.ReadLine());

while(a>1906 && a<2026){
        Console.WriteLine("Digite o mês do seu nascimento:");
        m = int.Parse(Console.ReadLine()); 
        
    while(m >= 1 && m <=12){
    Console.WriteLine("Digite o dia do seu nascimento:");
    d = int.Parse(Console.ReadLine());

        switch(m) {
            case 1: d >= 1 && d<=31 break; //jan
             if (a % 400 == 0){ 
                case 2: d >=1 && d <= 29 break; } //fevB
                else 
                case 2: d >=1 && d <= 28 break;//fev
            case 3: d >= 1 && d<=31 break; //mar
            case 4: d >= 1 && d<=30 break; //abr
            case 5: d >= 1 && d<=31 break; //mai
            case 6: d >= 1 && d<=30 break; //jun
            case 7: d >= 1 && d<=31 break; //jul
            case 8: d >= 1 && d<=31 break; //ago
            case 9: d >= 1 && d<=30 break; //set
            case 10: d >= 1 && d<=31 break; //out
            case 11: d >= 1 && d<=30 break; //nov
            case 12: d >= 1 && d<=31 break; //dez 
            
            Console.Write("Data incorreta" );
            
        }
    }
    
}

Console.Write($"A data do seu nascimento é:" {d}/{m}/{a});
nasc = int.Parse(Console.ReadLine())



