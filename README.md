### Hi there, I'm Lucas 👋

<p><em>Computer Science & Engineering student at <a href="https://www.imt-mines-ales.fr/">IMT Mines Alès
</a><img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> 
</em></p>

![github: Lucas Texier](https://img.shields.io/badge/-Github-black?style=flat-square&logo=Github&logoColor=white&link=https://github.com/LucasTexier/LucasTexier/)
![Linkedin: Lucas Texier](https://img.shields.io/badge/-Lucas-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/lucas-texier/)

class Lucas extends Student {
    
    final String username;
    String location;
    String favoriteLanguage;
    
    public Lucas() {
        username = "Lucas";
        location = "France";
        favoriteLanguage = "Python";
    }
    
    public School[] getSchools() {
        School[] mySchools = new School[2];
        
        String schoolName = "IMT Mines Alès";
        Degree degree = Degree.MASTER_OF_ENGINEERING;
        List<String> subjects = List.of("Computer Science", "Artificial Intelligence", "General Engineering");
        mySchools[0] = new School(schoolName, degree, subjects);
        
        return mySchools;
    }
    
    public String[] getGoals() {
        return new String[] {"Learn new things (Data science, machine learning, development)", "Contribute to OpenSource"};
    }
    
    public boolean isFreeToContact() {
        return true;
    }
}
