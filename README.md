# lammps-learning
#main.cpp
int main(int argc, **argv)
{
    LAMMPS *lammps = new LAMMPS(argc,argv,MPI_COMM_WORLD);// 实例化了一个lammps对象，并调用了LAMMPS类的构造函数
    lammps->input->file();                                // ？？？
    delete lammps;                                        // 删除lammps对象
}
