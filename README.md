BeastConfig
Example: SettingName=SettingValue;
File Ending: .bsf for example config.bsf
Written in C# (.Net Framework 4.8)
AddReference to BeastConfig.dll
Usage:
    using BeastConfig;
    BeastFile file1 = new BeastFile(pathtofile);
    file1.SetSetting("TestName", "TestValue");
    file1.Organize();
    Console.WriteLine(file1.UseSetting("TestName"));