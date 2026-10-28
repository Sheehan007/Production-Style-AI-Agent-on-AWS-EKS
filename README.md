# Production-Style-AI-Agent-on-AWS-EKS


The stack: 

                 -------------------------------------------------
                 |                  User / Client                |
                 |                REST API Requests              |
                 -------------------------------------------------
                                         |
                 -------------------------------------------------
                 |                AWS Load Balancer              |
                 |              public traffic routing           |
                 -------------------------------------------------
                                         |
                 -------------------------------------------------
                 |             Kubernetes on Amazon EKS          |
                 |        Deploy, recover and scale containers   |
                 -------------------------------------------------
                                         |
                 -------------------------------------------------
                 |           Docker + FastAPI + AI Agent         |
                 |        Python, tools and LLM Orchestration    |
                 -------------------------------------------------
                                         |
                 -------------------------------------------------
                 |             LLM API + Data Services           |
                 |          Model, database, retrieval, tools    |
                 -------------------------------------------------
