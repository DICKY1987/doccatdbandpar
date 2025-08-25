{
  "schemaName": "Master Project File Classification",
  "version": "1.0",
  "description": "A unified classification schema for organizing all project-related files, synthesized from three separate project environment baselines.",
  "categories": [
    {
      "categoryID": "CODE",
      "categoryName": "Source Code & Development",
      "description": "Contains all executable source code, scripts, and development resources, organized by programming language and framework.",
      "keywords": ["function", "class", "import", "export", "def", "var", "const", "source", "script", "test"],
      "subcategories": [
        {
          "categoryID": "CODE_PYTHON",
          "categoryName": "Python",
          "description": "Python source files, modules, packages, and notebooks.",
          "keywords": ["python", ".py", "django", "fastapi", "flask", "ipynb"],
          "subcategories": []
        },
        {
          "categoryID": "CODE_MQL",
          "categoryName": "MQL4/MQL5",
          "description": "Trading system code, including Expert Advisors, indicators, and scripts for MetaTrader.",
          "keywords": ["mql4", "mql5", ".mq4", ".mq5", "OrderSend", "EA", "indicator"],
          "subcategories": []
        },
        {
          "categoryID": "CODE_JAVASCRIPT",
          "categoryName": "JavaScript/TypeScript",
          "description": "Frontend components, Node.js services, and related web assets.",
          "keywords": ["javascript", "typescript", ".js", ".ts", "react", "node", "express"],
          "subcategories": []
        },
        {
            "categoryID": "CODE_POWERSHELL",
            "categoryName": "PowerShell",
            "description": "Windows automation and system management scripts.",
            "keywords": ["powershell", ".ps1", "cmdlet", "windows"],
            "subcategories": []
        },
        {
          "categoryID": "CODE_SQL",
          "categoryName": "SQL & Database Scripts",
          "description": "Database queries, schema definitions, and migration scripts.",
          "keywords": ["sql", "database", "select", "insert", "migration", "schema"],
          "subcategories": []
        }
      ]
    },
    {
      "categoryID": "INFRA",
      "categoryName": "Infrastructure & Deployment",
      "description": "Files related to Infrastructure as Code (IaC), containerization, orchestration, and CI/CD pipelines.",
      "keywords": ["infrastructure", "deployment", "docker", "kubernetes", "terraform", "ci/cd", ".tf", "dockerfile"],
      "subcategories": [
        {
          "categoryID": "INFRA_CONTAINERS",
          "categoryName": "Containerization",
          "description": "Dockerfile and Docker Compose files for building and running containers.",
          "keywords": ["docker", "docker-compose", "container"],
          "subcategories": []
        },
        {
          "categoryID": "INFRA_ORCHESTRATION",
          "categoryName": "Orchestration",
          "description": "Kubernetes manifests and other deployment orchestration files.",
          "keywords": ["kubernetes", "k8s", "deployment", "service", "helm"],
          "subcategories": []
        }
      ]
    },
    {
      "categoryID": "CONFIG",
      "categoryName": "Configuration & Settings",
      "description": "All configuration files for applications, systems, and environments.",
      "keywords": ["config", "settings", "json", "yaml", ".env", "ini", "properties"],
      "subcategories": [
        {
          "categoryID": "CONFIG_APP",
          "categoryName": "Application Configs",
          "description": "Configuration files specific to an application's behavior.",
          "keywords": ["application", "settings", "parameters", "feature-flags"],
          "subcategories": []
        },
        {
          "categoryID": "CONFIG_SECRETS",
          "categoryName": "Secrets & Environment",
          "description": "Environment-specific configurations, including secrets and connection strings. Handle with care.",
          "keywords": [".env", "secrets", "credentials", "production", "development"],
          "subcategories": []
        }
      ]
    },
    {
      "categoryID": "DATA",
      "categoryName": "Data & Analytics",
      "description": "Raw and processed data, analytics reports, database schemas, and data exports.",
      "keywords": ["data", "analytics", "csv", "json", "sql", "parquet", "report"],
      "subcategories": [
        {
            "categoryID": "DATA_RAW",
            "categoryName": "Raw Data",
            "description": "Original, unprocessed data from various sources.",
            "keywords": ["raw", "source", "unprocessed"],
            "subcategories": []
        },
        {
            "categoryID": "DATA_PROCESSED",
            "categoryName": "Processed Data",
            "description": "Cleaned, transformed, and enriched data ready for analysis.",
            "keywords": ["processed", "cleaned", "transformed"],
            "subcategories": []
        }
      ]
    },
    {
      "categoryID": "AUTOMATION",
      "categoryName": "Workflow & Process Automation",
      "description": "General-purpose automation scripts and workflow definitions that are not specific to AI systems.",
      "keywords": ["automation", "workflow", "orchestration", "pipeline", "trigger", "script"],
      "subcategories": []
    },
    {
      "categoryID": "AI_SYSTEMS",
      "categoryName": "AI Systems & Integration",
      "description": "All files related to AI/LLM integration, including prompt engineering, model configurations, and AI-driven workflows.",
      "keywords": ["ai", "claude", "llm", "anthropic", "prompt", "agent", "completion", "machine-learning"],
      "subcategories": [
        {
          "categoryID": "AI_PROMPTS",
          "categoryName": "Prompts & Templates",
          "description": "Prompt templates and files related to prompt engineering.",
          "keywords": ["prompt", "template", "chain-of-thought"],
          "subcategories": []
        },
        {
          "categoryID": "AI_WORKFLOWS",
          "categoryName": "AI-Driven Workflows",
          "description": "Workflows and automations that have an AI model as a core component.",
          "keywords": ["workflow", "agent", "orchestration", "claude-cli"],
          "subcategories": []
        }
      ]
    },
    {
      "categoryID": "DOCS",
      "categoryName": "Documentation",
      "description": "All documentation, including high-level architecture, technical guides, and standards.",
      "keywords": ["docs", "documentation", "guide", "readme", ".md", "architecture", "specifications"],
      "subcategories": [
        {
          "categoryID": "DOCS_ARCH",
          "categoryName": "Architecture & Specifications",
          "description": "High-level system design, architecture decision records (ADRs), and project specifications.",
          "keywords": ["architecture", "specifications", "design", "adr", "diagram"],
          "subcategories": []
        },
        {
          "categoryID": "DOCS_TECH",
          "categoryName": "Technical Guides",
          "description": "Detailed implementation instructions, API documentation, setup guides, and technical deep-dives.",
          "keywords": ["technical", "implementation", "api", "setup", "how-to"],
          "subcategories": []
        }
      ]
    },
    {
      "categoryID": "DOMAIN",
      "categoryName": "Domain-Specific Systems",
      "description": "Systems or modules related to a specific business domain.",
      "keywords": ["domain", "business", "expert"],
      "subcategories": [
        {
          "categoryID": "DOMAIN_TRADING",
          "categoryName": "Trading & Financial",
          "description": "Systems related to financial trading, including bots, indicators, and market data analysis.",
          "keywords": ["trading", "financial", "market", "expert-advisor", "risk"],
          "subcategories": []
        }
      ]
    },
    {
      "categoryID": "PROJECT",
      "categoryName": "Project Support",
      "description": "Files related to project management, collaboration, and analysis.",
      "keywords": ["project", "management", "tracking", "analysis", "collaboration"],
      "subcategories": [
        {
          "categoryID": "PROJECT_MGMT",
          "categoryName": "Management & Tracking",
          "description": "Project plans, scope documents, solution catalogs, and progress tracking files.",
          "keywords": ["tracking", "planning", "scope", "catalog", "deliverables"],
          "subcategories": []
        },
        {
          "categoryID": "PROJECT_COMMS",
          "categoryName": "Communication & Collaboration",
          "description": "Chat logs, meeting notes, and other collaborative artifacts.",
          "keywords": ["chat", "collaboration", "meeting", "notes", "conversation"],
          "subcategories": []
        }
      ]
    }
  ]
}