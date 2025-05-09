# Kusuna-0290-
import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button";

export default function TenjikuSite() { return ( <div className="p-4 space-y-6"> <h1 className="text-3xl font-bold text-center">Kusuna#0290 - Tenjiku Tribe</h1>

<Card className="bg-gray-100">
    <CardContent className="p-4">
      <h2 className="text-xl font-semibold mb-2">About Kusuna</h2>
      <p>
        Kusuna#0290 is one of the best players in Transformice. He played a lot of challenges—estimated at 175—and lost only five.
        He became famous in a short period of not more than three months. Among his most important achievements: he defeated ex top 6 EN (10-1)
        in just the second month of starting the game. He participated in multiple wars and won most of them within that same month.
        Playing 175 challenges in three months and winning 170 shows his consistency and dominance.
      </p>
      <p className="mt-2">
        With his sudden rise, we may witness even greater achievements. He revived the Tenjiku tribe in less than a week,
        inviting more than 150 players with the help of his vice, Ph1nky. They transformed the tribe from only 6 members to around 150.
        He is now the leader of one of the biggest tribes in Transformice — "Tenjiku".
        We expect big things from him in the future. We're still waiting for more updates from him, as he has not submitted any retirement announcement yet.
      </p>
    </CardContent>
  </Card>

  <div className="text-center">
    <Button className="text-white bg-black hover:bg-gray-800">
      Join Tenjiku Tribe
    </Button>
  </div>
</div>

); }

