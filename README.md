public static void main(String args[])
{
     static int i=0;
     static Student[] stud=new Student[5];
     Scanner sc= new Scanner(System.in);
     String marks=("Physics","Chemistry","Math","English","Language");
     int marks=sc.nextInt();
     while(true) 
     {
          int select;
          select=sc.nextInt();
          System.out.print("1.Add Student Record\n");
          System.out.print("2.Update Student Record\n");
          System.out.print("3.Delete Student Record\n");
          System.out.print("4.View Student Record\n");
          System.out.print("5.Exit");
          switch(select)
          {
              case 1:
                  addStud(stud);
                  break;
              case 2:
                  updateStud(stud);
                  break;
              case 3:
                  deleteStud(stud);
                  break;
              case 4:
                  viewStud(stud);
                  break;
              case 5:
                  return;
                default:
                    System.out.print("Invalid Option");
          }
     }
}
   
            
         
    
         
          
