```python
from typing import Dict, List

def Victorgesicht():
    """Security Analyst / Blue Team"""
    return {
        "blog": "[https://saragossa.pythonanywhere.com/](https://saragossa.pythonanywhere.com/)",
        "focus": "DFIR | SOC | DjangoDevSec"
    }

def get_skills() -> Dict[str, List[str]]:
    return {
        "low_level": ["Assembly (x86/x64)", "C++"],
        "operations": ["DFIR", "SOC Triage", "Malware Analysis", "SIEM/EDR"]
    }

