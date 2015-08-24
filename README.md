# Computer Graphics Gems JP 2015:5�D�u�X�L�j���O�����v �T���v���R�[�h
�{�R�[�h�́CComputer Graphics Gems JP 2015��5�́u�X�L�j���O�����v�ŏЉ�Ă���A���S���Y��"Smooth Skinning Decomposition with Rigid Bones"�̎����T���v���ł��D

## �r���h�Ǝ��s���@
�{�T���v���� Visual Studio 2013 Professional �v���W�F�N�g�Ƃ��č쐬���Ă��܂��D�܂��C�{�R�[�h�P�̂ł̓r���h�ł��܂���D���C�u�����Ƃ��āC[Eigen](http://eigen.tuxfamily.org/ "Eigen")�����[QuadProg++](http://quadprog.sourceforge.net/ "QuadProg++")���K�v�ł��D�Ȃ��C�r���h����ю��s�e�X�g�ɂ� Eigen 3.2.4 ����� QuadProg++ 1.2.1 ��p���܂����D

�܂��C���b�V���A�j���[�V�����̃T���v���f�[�^�� [Mesh Data from Deformation Transfer for Triangle Meshes](http://people.csail.mit.edu/sumner/research/deftransfer/data.html "Mesh Data from 
Deformation Transfer for Triangle Meshes")����_�E�����[�h���C����̃t�H���_�ɔz�u����K�v������܂��D

�r���h�Ǝ��s�̂��߂̍ł��ȒP�Ȏ菇�͎��̒ʂ�ł��D

1. Eigen�̃C���X�g�[���t�H���_�ɃC���N���[�h�p�X��ʂ��D
2. QuadProg++���_�E�����[�h���C���L��4�̃t�@�C����ssdr�t�H���_�ɃR�s�[����D
 * QuadProg++.hh
 * QuadProg++.cc
 * Array.hh
 * Array.cc
3. [Mesh Data from Deformation Transfer for Triangle Meshes](http://people.csail.mit.edu/sumner/research/deftransfer/data.html "Mesh Data from 
Deformation Transfer for Triangle Meshes")�̃y�[�W����uHorse gallop animation from the video.�v���_�E�����[�h���C���k�A�[�J�C�u�Ɋ܂܂��uhorse-gallop-01.obj�v����uhorse-gallop-reference.obj�v�̑S�Ă�obj�t�@�C���� ssdr/data �t�H���_�ɃR�s�[����D
4. Visual Studio��p���ăr���h�����s

## �v�Z�p�����[�^�̒���
SSDR�̎�Ȍv�Z�p�����[�^�́CHorseObject::OnInit���CHorseObject.cpp ��339�s�ڂ�����CssdrParam �\���̂Ɏw�肳��Ă��܂��D
* numIndices�F �e���_������Ɋ��蓖�Ă���ő�{�[����
* numMinBones�F ���_�A�j���[�V�����ߎ��ɗp����ŏ��{�[����
* numMaxIterations�F �ő唽����

�����3�̃p�����[�^�̕ύX���邱�ƂŁC����ɂƂ��Ȃ��v�Z���ʂ̕ω����m�F����������Ǝv���܂��D

## �Q�l����

1. Binh Huy Le and Zhigang Deng, Smooth Skinning Decomposition with Rigid Bones, ACM Transactions on Graphics, 31 (6), (2012), 199:1-199:10.
2. Binh Huy Le and Zhigang Deng, Robust and Accurate Skeletal Rigging from Mesh Sequences, ACM Transactions on Graphics, 33 (4), (2014), 84:1-84:10.

## �ύX����
1. 2015/08/24 ���Ō��J
