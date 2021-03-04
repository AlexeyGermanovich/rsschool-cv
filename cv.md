# Alexey Germanovich

_Minsk, Belarus_

## Contact information

**Phone:** +375(29)857-78-62
**E-mail** alexei.germanovich@yandex.ru

## Summary

## Skills

## Education

- Faculty of Information Technologies and Control of Belarusian State University of Informatics and Radioelectronics

## Work Experience

_August, 2019 - Present_ - C# Programmer

## Code Samples

```
private void LoadCfg()
        {
            UInt32 Result;
            string strTemp;

            //Set all configurations for the device according to the loaded file
            Result = Motion.mAcm_DevLoadConfig(m_DeviceHandle, AppDomain.CurrentDomain.BaseDirectory + "\\20001000.cfg");
            if (Result != (uint)Advantech.Motion.ErrorCode.SUCCESS)
            {
                strTemp = "Load Config Failed With Error Code: [0x" + Convert.ToString(Result, 16) + "]";
                ShowMessages(strTemp, Result);
                return;
            }
        }
```

## English

**B1 level**
