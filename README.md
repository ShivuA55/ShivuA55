class DataEnthusiast:
    def __init__(self):
        self.name = "Shivanand"
        self.role = "Aspiring Data Analyst"
        self.certification = "Post Graduation Certification in Data Analytics - Imarticus Learning"
        self.skills = ["Python", "SQL", "Data Visualization", "Machine Learning", "Statistics", "Power BI", "Tableau"]
        self.strengths = ["Problem Solving", "Logical Thinking", "Pattern Recognition", "Attention to Detail"]
        self.interests = ["Big Data", "AI & ML", "Predictive Analytics", "Business Intelligence"]
        self.hobbies = ["Coding", "Chess", "Gaming", "Reading Tech Blogs"]
        self.passion = "Transforming raw data into meaningful insights!"
    
    def display_profile(self):
        return f"""
        🚀 Meet {self.name} - A {self.role} 🚀
        🎓 Certification: {self.certification}
        🛠️ Skills: {', '.join(self.skills)}
        💡 Strengths: {', '.join(self.strengths)}
        📊 Interests: {', '.join(self.interests)}
        🎮 Hobbies: {', '.join(self.hobbies)}
        ❤️ Passion: {self.passion}
        """

# Creating an instance
shivanand = DataEnthusiast()
print(shivanand.display_profile())
