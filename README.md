# importcsv

This is a class to read the CSV file with vbs.
Quart processing is based on excel.

If you use ODBC's text driver, you can read CSV files that correspond to quote processing,
If you do not prepare schema.ini unintentional type recognition is done automatically or you can not process 256 or more columns,
I think whether there was a case where the limitation was not acceptable.

Processing speed aimed at powershell level.
* In the actual measurement at hand, it was faster than powershell unless a lot of quart processing was entered.

Since I will publish the source, I think whether it is easy to correspond to files derived from CSV format.
The appearance of powershell brings that VBS has gone with an out-of-date feeling, but I am pleased if we can extend the life even a little.

Please send us your comments / impressions.
Such as high-speed CSV parser in other languages, I will consider it.

---

���X�ɂȂ�܂����Avbs �� CSV �t�@�C����ǂݍ��ރN���X�ɂȂ�܂��B
�N�I�[�g������ excel �ɏ����Ă��܂��B

ODBC �� text driver �𗘗p����΁A�]������N�I�[�g�����ɑΉ����� CSV �t�@�C���̓ǂݍ��݂͂ł��܂������A
schema.ini ��p�ӂ��Ȃ��ƕs�{�ӂȌ^�F���������ł���Ă��܂�����A256 �J�����ȏ�̃J�����������ł��Ȃ�������ƁA
���������e�ł��Ȃ��ꍇ�����������Ǝv���܂��B

�������x�� powershell ���x����ڎw���܂����B
���茳�̎����ł́A�N�I�[�g��������������Ȃ���΁Apowershell ��葬�������ł��B

�\�[�X�����J���܂��̂ŁA���� CSV �t�@�C���ւ̑Ή����e�Ղɍs���邩�Ǝv���܂��B
powershell �̓o��ɂ��A����x�ꊴ���Y���Ă��� VBS �ł����A����ŏ����ł��������ł���΍K���ł��B

���ӌ�/�����z�A������܂����炨���肭�������B
���̌���ł̍���CSV�p�[�T�[�ȂǁA���v�]����܂����猟�����Ă݂܂��B

2018/05/01 biwaz@outlook.jp
