massive-shame
=============

namespace SingletonModel
{
    class Singleton
    {
        private Singleton single;
        private Singleton()
        { 
        }

        public Singleton GetInstance()
        {
            if (single==null)
            {
                single = new Singleton();
            }
            return single;
        }
    }
}
























