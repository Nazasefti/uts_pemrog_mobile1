# PEMROGRAMAN MOBILE UTS

# NAMA : NAZA SEFTI PRIANITA

# NIM : 312210306

# KELAS : TI.22.A3

# Soal

![Screenshot (20)](https://github.com/Nazasefti/uts_pemrog_mobile1/assets/115772516/142a870d-9bab-473a-8c2d-acb4afa580ba)

# Input

- AndroidManifest.xml

    <?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools">

    <application
        android:allowBackup="true"
        android:dataExtractionRules="@xml/data_extraction_rules"
        android:fullBackupContent="@xml/backup_rules"
        android:icon="@mipmap/ic_launcher"
        android:label="@string/app_name"
        android:roundIcon="@mipmap/ic_launcher_round"
        android:supportsRtl="true"
        android:theme="@style/Theme.HelloToast"
        tools:targetApi="31">
        <activity
            android:name=".MainToast"
            android:exported="true">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
    </application>
</manifest>
