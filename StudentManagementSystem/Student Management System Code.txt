/*
Maine ye ek Student Management System banaya hai 
jisme KCC INSTITUTE OF TECHNOLOGY AND MANAGEMENT KA HAI 
 Isme 3 setion hai 
 Each Section main 11 Student hai 
Alag Alag student ka pura record store kara hai 
like Name,Section,Roll no , Subject, Marks in each subject 
And the Total of marks 
 */
package StudentManagementSystem;

import java.util.Scanner;


public class Main {

     public static void main(String[] args) {
      //College Name
      System.out.println("KCC INSTITUTE OF TECHNOLOGY AND MANAGEMENT GREATER NOIDA");

      //Project Name
      System.out.println("STUDENT MANAGEMENT SYSTEM");

      
      // This is the Menu part of this project 
      System.out.println("========== MAIN MENU ==========");
      System.out.println("1. View Section");
      System.out.println("2. view Student");
      System.out.println("3. view Class CR");
      System.out.println("4. Manage Student Marks");
      System.out.println("5. view Report");
      System.out.println("6. Exit");
      
      Scanner sc = new Scanner(System.in);

      // yaha user ki choice puchi ja rahi ki vo kya dekhna chata hai 
      System.out.println("Enetr Your Choice: ");
      int Choice = sc.nextInt();

      switch (Choice) {
            case 1:
                  System.out.println(" View Section");
                  System.out.println("Total 3 Section");
                  

                  int Section = sc.nextInt();
                  switch (Section) {
                        case 1:
                              System.out.println("section A");
                              
                              break;
                         case 2:
                              System.out.println("section B");
                              
                              break;
                         case 3:
                              System.out.println("section C");
                              
                              break;
                  
                        default:
                              System.out.println("Invalid Setion");
                              break;
                  }
                  
                  break;
            case 2:

            /*agar koi student dekhna chata hai to pahle vo bataiga ki konse
            section ke student ko dekhna chata hai 
            usi section ke student dikhai dega use 
             */
                  System.out.println(" View Student");
                  System.out.println("Which Section Would You like to See");
                   int Sections = sc.nextInt();
                  switch (Sections) {
                        case 1:

                        // yaha Section A ke sare student hai 
                              System.out.println("section A");
                              System.out.println("Total Student 11");
                              System.out.println("1. Luna Evelyn CR");
                              System.out.println("2. MOhd Anas");
                              System.out.println("3. Akash Garg");
                              System.out.println("4. Mayank Sharma");
                              System.out.println("5. Aditya Kumar");
                              System.out.println("6. Sadhvi Pandey");
                              System.out.println("7. Ritka Kumari");
                              System.out.println("8. Vance");
                              System.out.println("9. Rohan");
                              System.out.println("10. Saif");
                              System.out.println("11. Monu");

                              
                              break;
                         case 2:
                              // yaha section B ke sare students hai
                              System.out.println("section B");
                               System.out.println("Total Student 11");
                              System.out.println("1. Luna  CR");
                              System.out.println("2. MOhd ");
                              System.out.println("3. Akash");
                              System.out.println("4. Mayank");
                              System.out.println("5. Aditya");
                              System.out.println("6. Sadhvi");
                              System.out.println("7. Ritka ");
                              System.out.println("8. Van");
                              System.out.println("9. Roh");
                              System.out.println("10. Sai");
                              System.out.println("11. Mon");

                              
                              break;
                         case 3:
                              // yaha section C ke sare students hai
                              System.out.println("section C");
                              System.out.println("Total Student 11");
                              System.out.println("1. Evelyn CR");
                              System.out.println("2. Anas");
                              System.out.println("3. Garg");
                              System.out.println("4. Sharma");
                              System.out.println("5. Kumar");
                              System.out.println("6. Pandey");
                              System.out.println("7. Kumari");
                              System.out.println("8. nce");
                              System.out.println("9. han");
                              System.out.println("10. aif");
                              System.out.println("11. onu");

                              
                              break;
                  
                        default:
                              System.out.println("Invalid Setion");
                              break;
                  }

                  break;
            case 3:
                  /*Agar koi kisi Setion ke CR ke bare me janna chata hai to 
                  pahle use setion batana padega ki kis section ke CR ke bare me 
                  janna hai use
                  fir use vahi section ke CR dikhaya jayega 
                  
                   */ 
                  System.out.println("View Class CR");
                   int Section2 = sc.nextInt();
                  switch (Section2) {
                        case 1:
                              System.out.println("section A");
                              System.out.println(" Luna Evelyn CR");
                              break;
                         case 2:
                              System.out.println("section B");
                              System.out.println(" Luna CR");
                              
                              break;
                         case 3:
                              System.out.println("section C");
                              System.out.println("Evelyn CR");
                              
                              break;
                  
                        default:
                              System.out.println("Invalid Setion");
                              break;
                  }

                  break;
            case 4:

            /*
            yaha student ke sab chij manage hungi 
            agar koi student ke marks janna chata hai to fir se use 
            pahle section batana padega kis section ke student ke marks dekhne hai 
             */
                  System.out.println(" Manage Student Marks");
                  int Section3 = sc.nextInt();
                  switch (Section3) {
                        case 1:
                              // yaha Section A ke sare students and unke marks
                              System.out.println("section A");
                              
                              //  fir use bataya jayega kis is section me kitne students 
                              // or agar use kisi specific students ke marks janne hai to use
                              // vo student batana padega 
                              //or us students ke marks hi dekhingef
                              System.out.println("Total 11 Students");

                        
                              int StudentSectionA = sc.nextInt();
                              switch (StudentSectionA) {
                                    
                                    case 1:
                                          System.out.println("1. Luna Evelyn CR");
                                          System.out.println("==Class Topper==");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=97");
                                          System.out.println("Sub3=95");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=99");
                                          System.out.println("Total Marks:487/500");

                                          break;
                                    case 2:
                                          System.out.println("2. MOhd Anas");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");
                                          break;
                                    case 3:
                                          System.out.println("3. Akash Garg");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=90");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:476/500");
                                          break;
                                    case 4:
                                          System.out.println("4. Mayank Sharma");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=90");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=90");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:468/500");
                                          break;
                                    case 5:
                                          System.out.println("5. Aditya Kumar");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=95");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=90");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=90");
                                          System.out.println("Total Marks:468/500");
                                          break;
                                    case 6:
                                          System.out.println("6. Sadhvi Pandey");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=90");
                                          System.out.println("Sub2=90");
                                          System.out.println("Sub3=90");
                                          System.out.println("Sub4=90");
                                          System.out.println("Sub5=90");
                                          System.out.println("Total Marks:450/500");
                                          break;
                                    case 7:
                                          System.out.println("7. Ritka Kumari");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=80");
                                          System.out.println("Sub2=80");
                                          System.out.println("Sub3=80");
                                          System.out.println("Sub4=80");
                                          System.out.println("Sub5=80");
                                          System.out.println("Total Marks:400/500");
                                          break;
                                    case 8:
                                          System.out.println("8. Vance");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");
                                          break;
                                    case 9:
                                          System.out.println("9. Rohan");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");
                                          break;
                                    case 10:
                                          System.out.println("10. Saif");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");
                                          break;
                                    case 11:
                                          System.out.println("11. Monu");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");
                                          break;

                                    default:
                                          System.out.println("Invalid Student");
                                          break;
                              }


                              
                              break;
                         case 2:
                              // yaha Section B ke sare students and unke marks
                              System.out.println("section B");
                              System.out.println("Total 11 Student");

                              int StudentSectionB = sc.nextInt();
                              switch (StudentSectionB) {
                                    
                                    case 1:
                                          System.out.println("1. Luna  CR");
                                          System.out.println("==Class Topper==");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=97");
                                          System.out.println("Sub3=95");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=99");
                                          System.out.println("Total Marks:487/500");

                                          break;
                                    case 2:
                                          System.out.println("2. MOhd ");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");
                                          break;
                                    case 3:
                                          System.out.println("3. Akash");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=90");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:476/500");
                                          break;
                                    case 4:
                                          System.out.println("4. Mayank");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=90");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=90");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:468/500");
                                          break;
                                    case 5:
                                          System.out.println("5. Aditya");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=95");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=90");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=90");
                                          System.out.println("Total Marks:468/500");
                                          break;
                                    case 6:
                                          System.out.println("6. Sadhvi");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=90");
                                          System.out.println("Sub2=90");
                                          System.out.println("Sub3=90");
                                          System.out.println("Sub4=90");
                                          System.out.println("Sub5=90");
                                          System.out.println("Total Marks:450/500");
                                          break;
                                    case 7:
                                          System.out.println("7. Ritka");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=80");
                                          System.out.println("Sub2=80");
                                          System.out.println("Sub3=80");
                                          System.out.println("Sub4=80");
                                          System.out.println("Sub5=80");
                                          System.out.println("Total Marks:400/500");
                                          break;
                                    case 8:
                                          System.out.println("8. Van");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");
                                          break;
                                    case 9:
                                          System.out.println("9. Roh");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");
                                          break;
                                    case 10:
                                          System.out.println("10. Sai");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");
                                          break;
                                    case 11:
                                          System.out.println("11. Mon");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");
                                          break;

                                    default:
                                          System.out.println("Invalid Student");
                                          break;
                              }
                              


                              
                              break;
                         case 3:
                              // yaha Section C ke sare students and unke marks
                              System.out.println("section C");
                              System.out.println("Total 11 Students");
                              int StudentSectionC = sc.nextInt();
                              switch (StudentSectionC) {
                                    
                                    case 1:
                                          System.out.println("1.Evelyn CR");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=97");
                                          System.out.println("Sub3=95");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=99");
                                          System.out.println("Total Marks:487/500");

                                          break;
                                    case 2:
                                          System.out.println("2.Anas");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");
                                          break;
                                    case 3:
                                          System.out.println("3. Garg");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=90");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:476/500");
                                          break;
                                    case 4:
                                          System.out.println("4. Sharma");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=90");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=90");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:468/500");
                                          break;
                                    case 5:
                                          System.out.println("5. Kumar");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=95");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=90");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=90");
                                          System.out.println("Total Marks:468/500");
                                          break;
                                    case 6:
                                          System.out.println("6. Pandey");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=90");
                                          System.out.println("Sub2=90");
                                          System.out.println("Sub3=90");
                                          System.out.println("Sub4=90");
                                          System.out.println("Sub5=90");
                                          System.out.println("Total Marks:450/500");
                                          break;
                                    case 7:
                                          System.out.println("7. Kumari");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=80");
                                          System.out.println("Sub2=80");
                                          System.out.println("Sub3=80");
                                          System.out.println("Sub4=80");
                                          System.out.println("Sub5=80");
                                          System.out.println("Total Marks:400/500");
                                          break;
                                    case 8:
                                          System.out.println("8.nce");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");
                                          break;
                                    case 9:
                                          System.out.println("9. han");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");
                                          break;
                                    case 10:
                                          System.out.println("10. aif");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");
                                          break;
                                    case 11:
                                          System.out.println("11. Monu");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");
                                          break;

                                    default:
                                          System.out.println("Invalid Student");
                                          break;
                              }

                              
                              break;
                  
                        default:
                              System.out.println("Invalid Setion");
                              break;
                  }
                  
                  break;
            case 5:
                  /*
                  yaha agar koi kisi student ke bare me complete information lena
                  chata ki Name,Section,Roll no ,Subject,Each subject marks,Total marks of this student
                   */
                  System.out.println("View Report");
                   int Section5 = sc.nextInt();
                  switch (Section5) {
                        case 1:
                              System.out.println("section A");
                              System.out.println("Total 11 Student in Section A");

                              int ViewStudent = sc.nextInt();
                              switch (ViewStudent) {
                                    case 1:
                                          System.out.println("1. Luna Evelyn CR");
                                          System.out.println("==Class Topper==");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=97");
                                          System.out.println("Sub3=95");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=99");
                                          System.out.println("Total Marks:487/500");

                                          break;
                                    case 2:
                                          System.out.println("2. MOhd Anas");
                                          System.out.println("2. MOhd Anas");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");

                                          break;
                                    case 3:
                                           System.out.println("3. Akash Garg");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=90");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:476/500");

                                           break;
                                    case 4:
                                          System.out.println("4. Mayank Sharma");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=90");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=90");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:468/500");

                                          break;
                                    case 5:
                                          System.out.println("5. Aditya Kumar");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=95");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=90");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=90");
                                          System.out.println("Total Marks:468/500");

                                          break;
                                    case 6:
                                          System.out.println("6. Sadhvi Pandey");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=90");
                                          System.out.println("Sub2=90");
                                          System.out.println("Sub3=90");
                                          System.out.println("Sub4=90");
                                          System.out.println("Sub5=90");
                                          System.out.println("Total Marks:450/500");

                                          break;
                                    case 7:
                                          System.out.println("7. Ritka Kumari");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=80");
                                          System.out.println("Sub2=80");
                                          System.out.println("Sub3=80");
                                          System.out.println("Sub4=80");
                                          System.out.println("Sub5=80");
                                          System.out.println("Total Marks:400/500");

                                          break;
                                    case 8:
                                          System.out.println("8. Vance");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");

                                          break;
                                    case 9:
                                          System.out.println("9. Rohan");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");

                                          break;
                                    case 10:
                                          System.out.println("10. Saif");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");


                                          break;
                                    case 11:
                                          System.out.println("11. Monu");
                                          System.out.println("Total Subject 5");
                                          System.out.println("Sub1=98");
                                          System.out.println("Sub2=95");
                                          System.out.println("Sub3=92");
                                          System.out.println("Sub4=98");
                                          System.out.println("Sub5=95");
                                          System.out.println("Total Marks:478/500");

                                          break;
                                    default:
                                          System.out.println("Invalid Student");
                                          break;
                              }
                              
                              
                              break;
                         case 2:
                              System.out.println("section B");
                               System.out.println("Total 11 Student in Section B");

                               int ChoiceStudentB = sc.nextInt();
                               switch (ChoiceStudentB) {

                                          case 1:
                                                System.out.println("Luna - CR");
                                                System.out.println("==Class Topper==");
                                                System.out.println("Total Subject 5");
                                                System.out.println("Sub1=98");
                                                System.out.println("Sub2=97");
                                                System.out.println("Sub3=95");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=99");
                                                System.out.println("Total Marks:487/500");

                                                break;

                                          case 2:
                                                System.out.println("Mohd");
                                                System.out.println("Total Subject 5");
                                                System.out.println("Sub1=98");
                                                System.out.println("Sub2=95");
                                                System.out.println("Sub3=92");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=95");
                                                System.out.println("Total Marks:478/500");

                                                break;

                                          case 3:
                                                System.out.println("Akash");
                                                 System.out.println("Total Subject 5");
                                                System.out.println("Sub1=98");
                                                System.out.println("Sub2=95");
                                                System.out.println("Sub3=90");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=95");
                                                System.out.println("Total Marks:476/500");


                                                break;

                                          case 4:
                                                System.out.println("Mayank");
                                                System.out.println("Total Subject 5");
                                                System.out.println("Sub1=90");
                                                System.out.println("Sub2=95");
                                                System.out.println("Sub3=90");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=95");
                                                System.out.println("Total Marks:468/500");
                                                break;

                                          case 5:
                                                System.out.println("Aditya");
                                                 System.out.println("Total Subject 5");
                                                System.out.println("Sub1=95");
                                                System.out.println("Sub2=95");
                                                System.out.println("Sub3=90");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=90");
                                                System.out.println("Total Marks:468/500");


                                                break;

                                          case 6:
                                                System.out.println("Sadhvi");
                                                System.out.println("Total Subject 5");
                                                System.out.println("Sub1=90");
                                                System.out.println("Sub2=90");
                                                System.out.println("Sub3=90");
                                                System.out.println("Sub4=90");
                                                System.out.println("Sub5=90");
                                                System.out.println("Total Marks:450/500");

                                                break;

                                          case 7:
                                                System.out.println("Ritika");
                                                System.out.println("Total Subject 5");
                                                System.out.println("Sub1=80");
                                                System.out.println("Sub2=80");
                                                System.out.println("Sub3=80");
                                                System.out.println("Sub4=80");
                                                System.out.println("Sub5=80");
                                                System.out.println("Total Marks:400/500");

                                                break;

                                          case 8:
                                                System.out.println("Van");
                                                 System.out.println("Total Subject 5");
                                                System.out.println("Sub1=98");
                                                System.out.println("Sub2=95");
                                                System.out.println("Sub3=92");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=95");
                                                System.out.println("Total Marks:478/500");

                                                break;

                                          case 9:
                                                System.out.println("Roh");
                                                 System.out.println("Total Subject 5");
                                                System.out.println("Sub1=98");
                                                System.out.println("Sub2=95");
                                                System.out.println("Sub3=92");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=95");
                                                System.out.println("Total Marks:478/500");
                                                break;

                                          case 10:
                                                System.out.println("Sai");
                                                System.out.println("Total Subject 5");
                                                System.out.println("Sub1=98");
                                                System.out.println("Sub2=95");
                                                System.out.println("Sub3=92");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=95");
                                                System.out.println("Total Marks:478/500");

                                                break;

                                          case 11:
                                                System.out.println("Mon");
                                                 System.out.println("Total Subject 5");
                                                System.out.println("Sub1=98");
                                                System.out.println("Sub2=95");
                                                System.out.println("Sub3=92");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=95");
                                                System.out.println("Total Marks:478/500");

                                                break;

                                          default:
                                                System.out.println("Invalid Student Choice");
                                                break;
                                          }

                              
                              break;
                         case 3:
                              System.out.println("section C");
                               System.out.println("Total 11 Student in Section C");
                               int ChoiceStudentC = sc.nextInt();
                               switch (ChoiceStudentC) {

                                          case 1:
                                                System.out.println("Evelyn - CR");
                                                System.out.println("Total Subject 5");
                                                System.out.println("Sub1=98");
                                                System.out.println("Sub2=97");
                                                System.out.println("Sub3=95");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=99");
                                                System.out.println("Total Marks:487/500");
                                                break;

                                          case 2:
                                                System.out.println("Anas");
                                                System.out.println("Total Subject 5");
                                                System.out.println("Sub1=98");
                                                System.out.println("Sub2=95");
                                                System.out.println("Sub3=92");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=95");
                                                System.out.println("Total Marks:478/500");

                                                break;

                                          case 3:
                                                System.out.println("Garg");
                                                System.out.println("Total Subject 5");
                                                System.out.println("Sub1=98");
                                                System.out.println("Sub2=95");
                                                System.out.println("Sub3=90");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=95");
                                                System.out.println("Total Marks:476/500");


                                                break;

                                          case 4:
                                                System.out.println("Sharma");
                                                System.out.println("Total Subject 5");
                                                System.out.println("Sub1=90");
                                                System.out.println("Sub2=95");
                                                System.out.println("Sub3=90");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=95");
                                                System.out.println("Total Marks:468/500");
                                                break;

                                          case 5:
                                                System.out.println("Kumar");
                                                System.out.println("Total Subject 5");
                                                System.out.println("Sub1=95");
                                                System.out.println("Sub2=95");
                                                System.out.println("Sub3=90");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=90");
                                                System.out.println("Total Marks:468/500");

                                                break;

                                          case 6:
                                                System.out.println("Pandey");
                                                System.out.println("Total Subject 5");
                                                System.out.println("Sub1=90");
                                                System.out.println("Sub2=90");
                                                System.out.println("Sub3=90");
                                                System.out.println("Sub4=90");
                                                System.out.println("Sub5=90");
                                                System.out.println("Total Marks:450/500");
                                                break;

                                          case 7:
                                                System.out.println("Kumari");
                                                System.out.println("Total Subject 5");
                                                System.out.println("Sub1=80");
                                                System.out.println("Sub2=80");
                                                System.out.println("Sub3=80");
                                                System.out.println("Sub4=80");
                                                System.out.println("Sub5=80");
                                                System.out.println("Total Marks:400/500");

                                                break;

                                          case 8:
                                                System.out.println("nce");
                                                 System.out.println("Total Subject 5");
                                                System.out.println("Sub1=98");
                                                System.out.println("Sub2=95");
                                                System.out.println("Sub3=92");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=95");
                                                System.out.println("Total Marks:478/500");

                                                
                                                break;

                                          case 9:
                                                System.out.println("han");
                                                System.out.println("Total Subject 5");
                                                System.out.println("Sub1=98");
                                                System.out.println("Sub2=95");
                                                System.out.println("Sub3=92");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=95");
                                                System.out.println("Total Marks:478/500");
                                                break;

                                          case 10:
                                                System.out.println("aif");
                                                System.out.println("Total Subject 5");
                                                System.out.println("Sub1=98");
                                                System.out.println("Sub2=95");
                                                System.out.println("Sub3=92");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=95");
                                                System.out.println("Total Marks:478/500");

                                                break;

                                          case 11:
                                                System.out.println("onu");
                                                System.out.println("Total Subject 5");
                                                System.out.println("Sub1=98");
                                                System.out.println("Sub2=95");
                                                System.out.println("Sub3=92");
                                                System.out.println("Sub4=98");
                                                System.out.println("Sub5=95");
                                                System.out.println("Total Marks:478/500");
                                                break;

                                          default:
                                                System.out.println("Invalid Student Choice");
                                                break;
                                          }


                              
                              break;
                  
                        default:
                              System.out.println("Invalid Setion");
                              break;
                  }
                  break;
            case 6:
                  // agar koi kuch nhi dekhna chata to easyly exit  kar sakta hai 
                  System.out.println(" Exit");
                  break;

            default:
                  System.out.println("Invalid Choice");
                  break;
      }

      


     

      
     } 
    
}
