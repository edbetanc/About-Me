# Hi, I'm Edwin Betancur, a.k.a edbetanc

class WhoAmI:
    """Class to introduce Edbetanc :)"""
    def __init__(self, visitor_name):
        self.user = "edbetanc"
        self.last_education = "B.S. Computer Engineering"
        print("Learing: {}".format(self.get_current_learning_tech_tools()))
        print("Well-Known: {}".format(self.get_well_known_tech_tools()))
        print("Hobbies: {}" .format(self.get_hobbies()))

     <font color="red"> def </font> get_current_learning_tech_tools(self):
        return(["AWS", "Kubernetes", "GitLab CI/CD", "Terraform", "Jenkins"])

    def get_well_known_tech_tools(self):
        return({
            "Middleware & IBM Tools": "Integration BUS, MQ, API Connect, Websphere Application Server,Apache Tomcat, Nginx",
            "Methodologies": "ITIL, SCRUM, PMP",
            "DevOps Tools": "Git, Linux, Kubernetes, Jenkins, Terraform, AWS CloudFormation",
            "Cloud Computing": "AWS, IBM CLOUD",
        })

    def get_hobbies(self):
        return(["Spend time with my family", "Learn cool tech things", "Traveling", "Basketball"])

edbetanc = WhoAmI("your_name")
