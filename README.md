```csharp
using UnityEngine;
using System.Collections.Generic;

public class EntityStats : MonoBehaviour
{
    public static EntityStats instance = null;

    public string name = "Luiz Passos";
    public string[] jobExperiences = { "Easy2Tech", "Embraer" };
    public string graduation = "Computer Science";
    public List<string> languagesAndEngines = new List<string> { ".py", ".js", ".cs", "Unity", "Godot" };
    public string[] databases = { "Oracle", "MySQL", "MSSQL" };
    public List<string> interests = new List<string> { "Game Development", "RPA", "Web Development", "DBA" };
    public string[] toolsAndFrameworks = { "Django", "Flask", "Pandas", "OCR", "OCV", "YOLO", "Pytorch", "JQuery" };
    public List<string> APIs = new List<string> { "OpenAI", "ElevenLabs", "BigDataCorp", "Discord", "Spotify" };

    void Awake()
    {
        if (instance == null)
        {
            instance = this;
        }
        else if (instance != this)
        {
            Destroy(gameObject);
        }

        DontDestroyOnLoad(gameObject);
    }
}
