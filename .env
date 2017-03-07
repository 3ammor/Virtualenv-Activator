echo 'select virtualenv (ML2/ML3)'
echo 'enter 'x' to abort'
STATE=0
while [ $STATE = 0 ]; do
        read VIRSION
        if [ "$VIRSION" = "2" ]; then
                source .ML2/bin/activate
                let STATE=1
        elif [ "$VIRSION" = "3" ]; then
                source .ML3/bin/activate
                let STATE=1
        elif [ "$VIRSION" = "2 -j" ]; then
                source .ML2/bin/activate
                jupyter notebook
                let STATE=1
        elif [ "$VIRSION" = "3 -j" ]; then
                source .ML3/bin/activate
                jupyter notebook
                let STATE=1
        elif [ "$VIRSION" = "x" ]; then
                let STATE=1
        else
                echo 'enter 2 or 3'
        fi
done
