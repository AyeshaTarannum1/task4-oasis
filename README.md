# task4-oasis        {  
            l.setText("Que2: Which one of the following is not a Java feature?");  
            jb[0].setText("Object-Oriented");jb[1].setText("Use of pointers");jb[2].setText("Portable");jb[3].setText("Dynamic and Extensible");  
        }  
        if(current==2)  
        {  
            l.setText("Que3: Which of these cannot be used for a variable name in Java?");  
            jb[0].setText("Identifier & keyword");jb[1].setText("Identifier");jb[2].setText("Keyword");jb[3].setText("None of the mentioned");  
        }  
        if(current==3)  
        {  
            l.setText("Que4: What is the extension of java code files?");  
            jb[0].setText(".js");jb[1].setText(".txt");jb[2].setText(".class");jb[3].setText(".java");  
        }  
        if(current==4)  
        {  
            l.setText("Que5: which of the following is not an OOPS concept in java?");  
            jb[0].setText("Polymorphism");jb[1].setText("Inheritance");jb[2].setText("Compilation");jb[3].setText("Encapsulation");  
        }  
        if(current==5)  
        {  
            l.setText("Que6: Which of these are selection statements in Java?");  
            jb[0].setText("break");jb[1].setText("continue");jb[2].setText("for()");jb[3].setText("if()");  
        }  
        if(current==6)  
        {  
            l.setText("Que7: Which one among these is not a class? ");  
            jb[0].setText("Swing");jb[1].setText("Actionperformed");jb[2].setText("ActionEvent");  
                        jb[3].setText("Button");  
        }  
        if(current==7)  
        {  
            l.setText("Que8: which one among these is not a function of Object class?");  
            jb[0].setText("toString");jb[1].setText("finalize");jb[2].setText("equals");  
                        jb[3].setText("getDocumentBase");         
        }  
        if(current==8)  
        {  
            l.setText("Que9: Which of the below is not Java profiler?");  
            jb[0].setText("JProfiler");jb[1].setText("Eclipse Profiler");jb[2].setText("JVM");jb[3].setText("JConsole");  
        }  
        if(current==9)  
        {  
            l.setText("Que10: Which one among these is not a valid component?");  
            jb[0].setText("JButton");jb[1].setText("JList");jb[2].setText("JButtonGroup");  
                        jb[3].setText("JTextArea");  
        }  
        l.setBounds(30,40,450,20);  
        for(int i=0,j=0;i<=90;i+=30,j++)  
            jb[j].setBounds(50,80+i,200,20);  
    }  
    boolean check()  
    {  
        if(current==0)  
            return(jb[1].isSelected());  
        if(current==1)  
            return(jb[1].isSelected());  
        if(current==2)  
            return(jb[2].isSelected());  
        if(current==3)  
            return(jb[0].isSelected());  
        if(current==4)  
            return(jb[2].isSelected());  
        if(current==5)  
            return(jb[3].isSelected());  
        if(current==6)  
            return(jb[1].isSelected());  
        if(current==7)  
            return(jb[3].isSelected());  
        if(current==8)  
            return(jb[2].isSelected());  
        if(current==9)  
            return(jb[2].isSelected());  
        return false;  
    } 
   
    
} 

//create the main class  
class OnlineExam  
{  
    //main() method start  
    public static void main(String arg[])  
    {  
        try  
        {  
            //create instance of the CreateLoginForm  
            login form = new login();  
            form.setSize(800,300);  //set size of the frame  
            form.setVisible(true);  //make form visible to the user  
        }  
        catch(Exception e)  
        {     
            //handle exception   
            JOptionPane.showMessageDialog(null, e.getMessage());  
        }  
    }  
} 

https://github.com/user-attachments/assets/8b7f1ac6-7838-4776-a6d4-387ab10893f5


