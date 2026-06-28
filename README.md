class AbdullahHashem:
    def __init__(self):
        self.name = "Abdullah Hashem"
        self.pronouns = ["he", "him"]
        self.location = "Egypt 🇪🇬"

        self.education = {
            "university": "Sasconi University",
            "faculty": "Faculty of Computers and Information",
            "specialization": "Cyber Security"
        }

        self.languages = [
            "Python",
            "C++"
        ]

        self.ask_me_about = [
            "Cyber Security",
            "Python",
            "C++",
            "Linux",
            "Networking",
            "Problem Solving"
        ]

        self.skills = {
            "Programming": [
                "Python",
                "C++"
            ],
            "Cyber Security": [
                "Network Security",
                "Linux Basics",
                "Ethical Hacking Fundamentals"
            ],
            "Tools": [
                "Git",
                "GitHub",
                "VS Code"
            ]
        }

        self.currently_learning = [
            "Advanced Python",
            "Advanced C++",
            "Penetration Testing",
            "Web Security",
            "Linux Administration"
        ]

        self.current_focus = (
            "Building cybersecurity tools with Python "
            "and becoming a professional Cyber Security Engineer."
        )

        self.goal = (
            "Become a Penetration Tester and Security Researcher."
        )

    def __str__(self):
        return f"{self.name} | Cyber Security Student | Python & C++ Developer"


me = AbdullahHashem()
print(me)
