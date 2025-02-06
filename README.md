```csharp
using UnityEngine;
using System.Collections.Generic;

public class EntityStats : MonoBehaviour
{
    public static EntityStats instance = null;

    public string name = "Luiz Passos";
    public string[] jobExperiences = { "Easy2Tech", "Embraer", "Quero Educação" };
    public string graduation = "Computer Science";
    public List<string> languagesAndEngines = new List<string> { ".py", ".js", ".cs", "Unity", "Godot" };
    public string[] databases = { "Oracle", "MySQL", "MSSQL", "Trino SQL", "DataBricks" };
    public List<string> interests = new List<string> { "Game Development", "Data Analysis", "Data Science", "Business Intelligence" };
    public string[] toolsAndFrameworks = {"PySpark", "DataBricks", "OCV", "YOLO", "Pytorch", "Django", "Flask", "Pandas", "OCR", , "JQuery" };
    public List<string> APIs = new List<string> { "OpenAI", "ElevenLabs", "BigDataCorp", "Discord", "Spotify" };
    public List<string> Tools =  new List<string> {"Power BI", "Metabase", "Databricks", "Power Automation", "Excel", "SAP"};

}
