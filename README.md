# Hi, I'm Edwin Betancur, a.k.a edbetanc

class WhoAmI:
    """Class to introduce Edbetanc :)"""
    def __init__(self, visitor_name):
        self.user = "san99tiago"
        self.last_education = "B.S. Mechatronics Engineering"
        print("Learing: {}".format(self.get_current_learning_tech_tools()))
        print("Well-Known: {}".format(self.get_well_known_tech_tools()))
        print("Hobbies: {}" .format(self.get_hobbies()))

    def get_current_learning_tech_tools(self):
        return(["Advanced AWS Deployments", "Kubernetes", "GitLab CI/CD", "Complex Terraform Workflows", "Cryptography"])

    def get_well_known_tech_tools(self):
        return({
            "Backend & Frontend Tools": "Spring, Express, Flask, FastAPI & HTML, CSS, JS, SASS, React",
            "Databases": "MySQL, SQLite, MariaDB & MongoDB, DynamoDB, Elasticsearch",
            "DevOps Tools": "SCM, Git, Linux Background, Docker, Kubernetes, Jenkins, Azure Pipelines, Azure Extensions, SonarQube, Packer, Terraform, AWS CloudFormation, Ansible, OWASP",
            "Cloud Computing": "AWS (multiple resources with best architecture practices and IaC approach)",
            "Servers": "IBM Websphere Application Server, IBM MQ, Apache Tomcat, Nginx",
            "Computer Vision & IoT": "OpenCV, Pillow, Darknet & ESP8266, NodeMCU, RaspberryPi, RFModules, Postman",
            "Data Science": "Matplotlib, Numpy, Pandas, Seaborn, Pyplot",
            "Robotics & Machine Learning": "ROS, Python, Arduino & Scikit-learn, TensorFlow, CVXPY"
        })

    def get_hobbies(self):
        return(["Piano", "Learn cool tech things", "Listen to audiobooks", "Juggle"])

santi = WhoAmI("your_name")
